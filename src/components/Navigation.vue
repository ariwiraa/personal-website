<template>
  <nav class="fixed top-0 w-full bg-gradient-to-r from-white/95 via-blue-50/95 to-purple-50/95 backdrop-blur-md border-b border-gradient-to-r from-blue-200/50 to-purple-200/50 z-50 transition-all duration-300" :class="{ 'shadow-lg': scrolled }">
    <!-- Progress Bar -->
    <div class="absolute bottom-0 left-0 h-0.5 bg-gradient-to-r from-blue-500 to-purple-600 transition-all duration-300" :style="{ width: scrollProgress + '%' }"></div>
    
    <div class="container-max">
      <div class="flex justify-between items-center py-4 px-4 sm:px-6 lg:px-8">
        <!-- Simple Logo -->
        <div class="flex items-center">
          <div class="text-xl font-bold bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent">
            Ari Wira Atmaja
          </div>
        </div>
        
        <!-- Desktop Navigation -->
        <div class="hidden md:flex space-x-1">
          <a v-for="item in navItems" :key="item.id" 
             :href="item.href" 
             @click="smoothScroll(item.href)"
             class="relative px-4 py-2 rounded-lg text-sm font-medium transition-all duration-300 group"
             :class="activeSection === item.id ? 'text-white bg-gradient-to-r from-blue-500 to-purple-600 shadow-lg' : 'text-secondary-600 hover:text-white hover:bg-gradient-to-r hover:from-blue-500/80 hover:to-purple-600/80'">
            {{ item.name }}
            <span v-if="activeSection === item.id" class="absolute -bottom-1 left-1/2 transform -translate-x-1/2 w-1 h-1 bg-white rounded-full"></span>
          </a>
        </div>
        
        <!-- Mobile Menu Button -->
        <button @click="toggleMobileMenu" class="md:hidden p-2 rounded-lg hover:bg-gradient-to-r hover:from-blue-100 hover:to-purple-100 transition-all duration-300">
          <svg class="w-6 h-6 transition-transform duration-300" :class="{ 'rotate-90': mobileMenuOpen }" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path v-if="!mobileMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg>
        </button>
      </div>
      
      <!-- Mobile Menu -->
      <div v-if="mobileMenuOpen" class="md:hidden border-t border-gradient-to-r from-blue-200/50 to-purple-200/50 bg-gradient-to-r from-blue-50/50 to-purple-50/50 backdrop-blur-sm">
        <div class="px-4 py-3 space-y-2">
          <a v-for="item in navItems" :key="item.id"
             :href="item.href" 
             @click="handleMobileClick(item.href)"
             class="block px-4 py-3 rounded-lg text-sm font-medium transition-all duration-300"
             :class="activeSection === item.id ? 'text-white bg-gradient-to-r from-blue-500 to-purple-600 shadow-md' : 'text-secondary-600 hover:text-white hover:bg-gradient-to-r hover:from-blue-500/80 hover:to-purple-600/80'">
            {{ item.name }}
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navigation',
  data() {
    return {
      mobileMenuOpen: false,
      scrolled: false,
      scrollProgress: 0,
      activeSection: 'hero',
      navItems: [
        { id: 'about', name: 'About', href: '#about' },
        { id: 'skills', name: 'Skills', href: '#skills' },
        { id: 'projects', name: 'Projects', href: '#projects' },
        { id: 'contact', name: 'Contact', href: '#contact' }
      ]
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll)
    this.handleScroll()
  },
  beforeUnmount() {
    window.removeEventListener('scroll', this.handleScroll)
  },
  methods: {
    toggleMobileMenu() {
      this.mobileMenuOpen = !this.mobileMenuOpen
    },
    closeMobileMenu() {
      this.mobileMenuOpen = false
    },
    handleMobileClick(href) {
      this.smoothScroll(href)
      this.closeMobileMenu()
    },
    smoothScroll(href) {
      const targetId = href.substring(1)
      const targetElement = document.getElementById(targetId)
      
      if (targetElement) {
        const offsetTop = targetElement.offsetTop - 80 // Account for fixed navbar
        window.scrollTo({
          top: offsetTop,
          behavior: 'smooth'
        })
      }
    },
    handleScroll() {
      const scrollTop = window.pageYOffset
      const docHeight = document.documentElement.scrollHeight - window.innerHeight
      
      // Update scroll state
      this.scrolled = scrollTop > 50
      
      // Update scroll progress
      this.scrollProgress = (scrollTop / docHeight) * 100
      
      // Update active section
      this.updateActiveSection()
    },
    updateActiveSection() {
      const sections = ['hero', 'about', 'skills', 'projects', 'contact']
      const scrollPosition = window.pageYOffset + 100
      
      for (let i = sections.length - 1; i >= 0; i--) {
        const section = document.getElementById(sections[i])
        if (section && section.offsetTop <= scrollPosition) {
          this.activeSection = sections[i]
          break
        }
      }
    }
  }
}
</script>