<template>
  <section id="projects" class="section-padding bg-gradient-to-br from-white to-gray-50">
    <div class="container-max">
      <!-- Header dengan animasi -->
      <div class="text-center mb-20">
        <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-full mb-6">
          <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
          </svg>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-secondary-900 mb-6 bg-gradient-to-r from-primary-600 to-accent-600 bg-clip-text text-transparent">
          Featured Projects
        </h2>
        <p class="text-xl text-secondary-600 max-w-3xl mx-auto leading-relaxed">
          Showcase of my best work demonstrating 
          <span class="font-semibold text-primary-600">technical skills</span> and 
          <span class="font-semibold text-accent-600">problem-solving</span> abilities
        </p>
      </div>
      <!-- Projects Grid -->
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
        <!-- Project 1 -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-primary-500 to-accent-500"></div>
          <div class="h-48 bg-gradient-to-br from-primary-100 to-primary-200 rounded-lg mb-6 flex items-center justify-center group-hover:scale-105 transition-transform">
            <div class="w-16 h-16 bg-white rounded-2xl flex items-center justify-center shadow-lg">
              <svg class="w-8 h-8 text-primary-600" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 2L2 7v10c0 5.55 3.84 9.95 9 11 5.16-1.05 9-5.45 9-11V7l-10-5z"/>
              </svg>
            </div>
          </div>
          <div class="flex items-start mb-4">
            <div class="w-12 h-12 bg-gradient-to-br from-primary-100 to-accent-100 rounded-xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">E-Commerce API</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-primary-500 to-accent-500 rounded-full"></div>
            </div>
          </div>
          <p class="text-secondary-600 mb-6 leading-relaxed">RESTful API for e-commerce platform with user authentication, product management, and order processing.</p>
          <div class="flex flex-wrap gap-2 mb-6">
            <span class="bg-gradient-to-r from-orange-50 to-red-50 text-orange-800 px-3 py-1 rounded-full text-sm font-medium">Java</span>
            <span class="bg-gradient-to-r from-green-50 to-emerald-50 text-green-800 px-3 py-1 rounded-full text-sm font-medium">Spring Boot</span>
            <span class="bg-gradient-to-r from-blue-50 to-cyan-50 text-blue-800 px-3 py-1 rounded-full text-sm font-medium">PostgreSQL</span>
          </div>
          <div class="flex space-x-4">
            <a href="https://github.com/ariwiraa/ecommerce" class="flex items-center text-primary-600 hover:text-primary-700 font-semibold transition-colors">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
              </svg>
              View Code
            </a>
            <a href="#" class="flex items-center text-accent-600 hover:text-accent-700 font-semibold transition-colors">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
              </svg>
              Live Demo
            </a>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-accent-500 to-secondary-500"></div>
          <div class="h-48 bg-gradient-to-br from-accent-100 to-accent-200 rounded-lg mb-6 flex items-center justify-center group-hover:scale-105 transition-transform">
            <div class="w-16 h-16 bg-white rounded-2xl flex items-center justify-center shadow-lg">
              <svg class="w-8 h-8 text-accent-600" fill="currentColor" viewBox="0 0 24 24">
                <path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-5 14H7v-2h7v2zm3-4H7v-2h10v2zm0-4H7V7h10v2z"/>
              </svg>
            </div>
          </div>
          <div class="flex items-start mb-4">
            <div class="w-12 h-12 bg-gradient-to-br from-accent-100 to-secondary-100 rounded-xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-6 h-6 text-accent-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">Social Media API</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-accent-500 to-secondary-500 rounded-full"></div>
            </div>
          </div>
          <p class="text-secondary-600 mb-6 leading-relaxed">RESTful API for social media platform with user authentication, post management, and comment functionality.</p>
          <div class="flex flex-wrap gap-2 mb-6">
            <span class="bg-gradient-to-r from-cyan-50 to-blue-50 text-cyan-800 px-3 py-1 rounded-full text-sm font-medium">Go</span>
            <span class="bg-gradient-to-r from-blue-50 to-indigo-50 text-blue-800 px-3 py-1 rounded-full text-sm font-medium">Gin</span>
            <span class="bg-gradient-to-r from-orange-50 to-yellow-50 text-orange-800 px-3 py-1 rounded-full text-sm font-medium">PostgreSQL</span>
          </div>
          <div class="flex space-x-4">
            <a href="https://github.com/ariwiraa/my-gram" class="flex items-center text-primary-600 hover:text-primary-700 font-semibold transition-colors">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
              </svg>
              View Code
            </a>
            <a href="#" class="flex items-center text-accent-600 hover:text-accent-700 font-semibold transition-colors">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
              </svg>
              Live Demo
            </a>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-secondary-500 to-primary-500"></div>
          <div class="h-48 bg-gradient-to-br from-secondary-100 to-secondary-200 rounded-lg mb-6 flex items-center justify-center group-hover:scale-105 transition-transform">
            <div class="w-16 h-16 bg-white rounded-2xl flex items-center justify-center shadow-lg">
              <svg class="w-8 h-8 text-secondary-600" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>
              </svg>
            </div>
          </div>
          <div class="flex items-start mb-4">
            <div class="w-12 h-12 bg-gradient-to-br from-secondary-100 to-primary-100 rounded-xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-6 h-6 text-secondary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">Forum API</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-secondary-500 to-primary-500 rounded-full"></div>
            </div>
          </div>
          <p class="text-secondary-600 mb-6 leading-relaxed">A comprehensive forum API project developed during Dicoding's Backend Expert course, featuring robust user authentication, thread management, and comment moderation capabilities.</p>
          <div class="flex flex-wrap gap-2 mb-6">
            <span class="bg-gradient-to-r from-orange-50 to-red-50 text-orange-800 px-3 py-1 rounded-full text-sm font-medium">Java Script</span>
            <span class="bg-gradient-to-r from-green-50 to-emerald-50 text-green-800 px-3 py-1 rounded-full text-sm font-medium">HapiJS</span>
            <span class="bg-gradient-to-r from-blue-50 to-cyan-50 text-blue-800 px-3 py-1 rounded-full text-sm font-medium">PostgreSQL</span>
          </div>
          <div class="flex space-x-4">
            <a href="https://github.com/ariwiraa/forum-api" class="flex items-center text-primary-600 hover:text-primary-700 font-semibold transition-colors">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
              </svg>
              View Code
            </a>
            <a href="#" class="flex items-center text-accent-600 hover:text-accent-700 font-semibold transition-colors">
              <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
              </svg>
              Live Demo
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>