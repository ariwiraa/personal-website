<template>
  <section class="relative pt-20 section-padding bg-gradient-to-br from-white via-primary-50 to-accent-50 overflow-hidden">
    <!-- Background Decorative Elements -->
    <div class="absolute inset-0 overflow-hidden">
      <div class="absolute -top-40 -right-40 w-80 h-80 bg-gradient-to-br from-primary-200 to-accent-200 rounded-full opacity-20 blur-3xl animate-pulse"></div>
      <div class="absolute -bottom-40 -left-40 w-80 h-80 bg-gradient-to-br from-accent-200 to-primary-200 rounded-full opacity-20 blur-3xl animate-pulse animation-delay-1000"></div>
      <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-96 h-96 bg-gradient-to-br from-primary-100 to-accent-100 rounded-full opacity-10 blur-3xl"></div>
    </div>

    <div class="container-max relative z-10">
      <div class="text-center">
        <!-- Avatar/Profile Section -->
        <div class="mb-8 animate-fade-in">
          <div class="inline-flex items-center justify-center w-32 h-32 bg-gradient-to-br from-primary-500 to-accent-500 rounded-full mb-6 shadow-2xl relative">
            <div class="absolute inset-2 bg-white rounded-full flex items-center justify-center">
              <svg class="w-16 h-16 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
              </svg>
            </div>
            <!-- Floating rings -->
            <div class="absolute inset-0 rounded-full border-2 border-primary-300 animate-ping opacity-30"></div>
            <div class="absolute inset-0 rounded-full border-2 border-accent-300 animate-ping opacity-30 animation-delay-500"></div>
          </div>
        </div>

        <!-- Main Content -->
        <div class="animate-slide-up">
          <!-- Greeting -->
          <div class="mb-4">
            <span class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-primary-100 to-accent-100 rounded-full text-sm font-medium text-primary-700 border border-primary-200">
              <span class="w-2 h-2 bg-green-400 rounded-full mr-2 animate-pulse"></span>
              Available for opportunities
            </span>
          </div>

          <!-- Name with enhanced typography -->
          <h1 class="text-5xl md:text-7xl font-bold mb-6 animate-slide-up animation-delay-200">
            <span class="bg-gradient-to-r from-secondary-900 via-primary-600 to-accent-600 bg-clip-text text-transparent">
              Ari Wira Atmaja
            </span>
          </h1>

          <!-- Enhanced description -->
          <div class="mb-8 animate-slide-up animation-delay-400">
            <p class="text-2xl md:text-3xl font-light text-secondary-700 mb-4 max-w-4xl mx-auto leading-relaxed">
              Junior Backend Developer
            </p>
            <p class="text-lg md:text-xl text-secondary-600 max-w-3xl mx-auto leading-relaxed">
              Crafting robust server-side solutions with 
              <span class="font-semibold text-primary-600 relative">
                Java
                <span class="absolute -bottom-1 left-0 w-full h-0.5 bg-gradient-to-r from-primary-500 to-transparent"></span>
              </span>, 
              <span class="font-semibold text-accent-600 relative">
                Spring Boot
                <span class="absolute -bottom-1 left-0 w-full h-0.5 bg-gradient-to-r from-accent-500 to-transparent"></span>
              </span>, 
              <span class="font-semibold text-primary-600 relative">
                Go
                <span class="absolute -bottom-1 left-0 w-full h-0.5 bg-gradient-to-r from-primary-500 to-transparent"></span>
              </span> 
              and modern database technologies
            </p>
          </div>

          <!-- Enhanced CTA Buttons -->
          <div class="flex flex-col sm:flex-row gap-4 justify-center items-center animate-slide-up animation-delay-600">
            <a href="#projects" class="group btn-primary relative overflow-hidden">
              <span class="relative z-10 flex items-center">
                <svg class="w-5 h-5 mr-2 group-hover:rotate-12 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                </svg>
                View My Work
              </span>
              <div class="absolute inset-0 bg-gradient-to-r from-primary-600 to-accent-600 transform scale-x-0 group-hover:scale-x-100 transition-transform origin-left"></div>
            </a>
            
            <a href="#contact" class="group btn-secondary relative overflow-hidden">
              <span class="relative z-10 flex items-center">
                <svg class="w-5 h-5 mr-2 group-hover:scale-110 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                </svg>
                Get In Touch
              </span>
            </a>
            
            <a href="/CV_20250708.pdf" target="_blank" class="group btn-secondary relative overflow-hidden">
              <span class="relative z-10 flex items-center">
                <svg class="w-5 h-5 mr-2 group-hover:translate-y-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
                </svg>
                Download Resume
              </span>
            </a>
          </div>

          <!-- Stats/Highlights -->
          <div class="mt-16 grid grid-cols-1 md:grid-cols-3 gap-8 max-w-4xl mx-auto animate-slide-up animation-delay-800">
            <div class="text-center group">
              <div class="w-16 h-16 bg-gradient-to-br from-primary-100 to-accent-100 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                </svg>
              </div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">2+</h3>
              <p class="text-secondary-600">Years Learning</p>
            </div>
            
            <div class="text-center group">
              <div class="w-16 h-16 bg-gradient-to-br from-accent-100 to-primary-100 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-8 h-8 text-accent-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                </svg>
              </div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">5+</h3>
              <p class="text-secondary-600">Projects Built</p>
            </div>
            
            <div class="text-center group">
              <div class="w-16 h-16 bg-gradient-to-br from-primary-100 to-accent-100 rounded-2xl flex items-center justify-center mx-auto mb-4 group-hover:scale-110 transition-transform">
                <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
                </svg>
              </div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">4</h3>
              <p class="text-secondary-600">Tech Stacks</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Scroll indicator -->
    <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce">
      <div class="w-6 h-10 border-2 border-primary-300 rounded-full flex justify-center">
        <div class="w-1 h-3 bg-primary-500 rounded-full mt-2 animate-pulse"></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection'
}
</script>