<template>
  <section id="about" class="section-padding bg-gradient-to-br from-white to-gray-50">
    <div class="container-max">
      <!-- Header dengan animasi -->
      <div class="text-center mb-20">
        <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-full mb-6">
          <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path>
          </svg>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-secondary-900 mb-6 bg-gradient-to-r from-primary-600 to-accent-600 bg-clip-text text-transparent">
          About Me
        </h2>
        <p class="text-xl text-secondary-600 max-w-3xl mx-auto leading-relaxed">
          Passionate junior backend developer with a focus on building 
          <span class="font-semibold text-primary-600">scalable</span> and 
          <span class="font-semibold text-accent-600">efficient</span> server-side applications
        </p>
      </div>

      <!-- Main Content dengan Grid Modern -->
      <div class="grid lg:grid-cols-3 gap-8 mb-16">
        <!-- Stats Cards -->
        <div class="lg:col-span-1 space-y-6">
          <div class="group card hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 border-l-4 border-primary-500">
            <div class="flex items-center mb-4">
              <div class="w-12 h-12 bg-primary-100 rounded-xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
                <svg class="w-6 h-6 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-bold text-secondary-900">Experience Level</h3>
                <p class="text-primary-600 font-semibold">Junior Backend Developer</p>
              </div>
            </div>
          </div>

          <div class="group card hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 border-l-4 border-accent-500">
            <div class="flex items-center mb-4">
              <div class="w-12 h-12 bg-accent-100 rounded-xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
                <svg class="w-6 h-6 text-accent-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z"></path>
                </svg>
              </div>
              <div>
                <h3 class="text-lg font-bold text-secondary-900">Specialization</h3>
                <p class="text-accent-600 font-semibold">Backend & Database</p>
              </div>
            </div>
          </div>

          <div class="group card hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 border-l-4 border-secondary-500">
            <h3 class="text-lg font-bold text-secondary-900 mb-4 flex items-center">
              <svg class="w-5 h-5 mr-2 text-secondary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path>
              </svg>
              Focus Areas
            </h3>
            <div class="space-y-3">
              <div class="flex items-center text-secondary-600 hover:text-primary-600 transition-colors">
                <div class="w-2 h-2 bg-primary-500 rounded-full mr-3 animate-pulse"></div>
                RESTful API Development
              </div>
              <div class="flex items-center text-secondary-600 hover:text-primary-600 transition-colors">
                <div class="w-2 h-2 bg-accent-500 rounded-full mr-3 animate-pulse"></div>
                Database Architecture
              </div>
              <div class="flex items-center text-secondary-600 hover:text-primary-600 transition-colors">
                <div class="w-2 h-2 bg-secondary-500 rounded-full mr-3 animate-pulse"></div>
                Microservices Design
              </div>
              <div class="flex items-center text-secondary-600 hover:text-primary-600 transition-colors">
                <div class="w-2 h-2 bg-primary-500 rounded-full mr-3 animate-pulse"></div>
                Performance Optimization
              </div>
            </div>
          </div>
        </div>

        <!-- Main Content -->
        <div class="lg:col-span-2 space-y-8">
          <!-- What I Do Card -->
          <div class="card group hover:shadow-2xl transition-all duration-300 relative overflow-hidden">
            <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-primary-500 via-accent-500 to-secondary-500"></div>
            <div class="flex items-start mb-6">
              <div class="w-14 h-14 bg-gradient-to-br from-primary-100 to-accent-100 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
                <svg class="w-7 h-7 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
                </svg>
              </div>
              <div>
                <h3 class="text-2xl font-bold text-secondary-900 mb-2">What I Do</h3>
                <div class="w-16 h-1 bg-gradient-to-r from-primary-500 to-accent-500 rounded-full"></div>
              </div>
            </div>
            <p class="text-secondary-600 leading-relaxed text-lg mb-6">
              I build <span class="font-semibold text-primary-600">robust backend systems</span> using modern technologies like 
              <span class="inline-flex items-center bg-primary-100 text-primary-800 px-2 py-1 rounded-md text-sm font-medium mx-1">Java</span> with 
              <span class="inline-flex items-center bg-accent-100 text-accent-800 px-2 py-1 rounded-md text-sm font-medium mx-1">Spring Boot</span> and 
              <span class="inline-flex items-center bg-secondary-100 text-secondary-800 px-2 py-1 rounded-md text-sm font-medium mx-1">Go</span> with 
              <span class="inline-flex items-center bg-primary-100 text-primary-800 px-2 py-1 rounded-md text-sm font-medium mx-1">Gin framework</span>.
            </p>
            <div class="grid md:grid-cols-2 gap-4">
              <div class="flex items-center text-secondary-600">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                </svg>
                Database Schema Design
              </div>
              <div class="flex items-center text-secondary-600">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                </svg>
                Scalable API Development
              </div>
              <div class="flex items-center text-secondary-600">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                </svg>
                Code Best Practices
              </div>
              <div class="flex items-center text-secondary-600">
                <svg class="w-5 h-5 text-green-500 mr-3" fill="currentColor" viewBox="0 0 20 20">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"></path>
                </svg>
                Performance Optimization
              </div>
            </div>
          </div>

          <!-- Current Goals Card -->
          <div class="card group hover:shadow-2xl transition-all duration-300 relative overflow-hidden">
            <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-accent-500 via-secondary-500 to-primary-500"></div>
            <div class="flex items-start mb-6">
              <div class="w-14 h-14 bg-gradient-to-br from-accent-100 to-secondary-100 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
                <svg class="w-7 h-7 text-accent-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
                </svg>
              </div>
              <div>
                <h3 class="text-2xl font-bold text-secondary-900 mb-2">Current Goals</h3>
                <div class="w-16 h-1 bg-gradient-to-r from-accent-500 to-secondary-500 rounded-full"></div>
              </div>
            </div>
            <p class="text-secondary-600 leading-relaxed text-lg mb-6">
              Continuously learning and improving my skills in 
              <span class="font-semibold text-accent-600">cloud technologies</span>, 
              <span class="font-semibold text-secondary-600">containerization</span>, and 
              <span class="font-semibold text-primary-600">distributed systems</span> 
              to build more scalable and resilient applications.
            </p>
            <div class="flex flex-wrap gap-3">
              <span class="inline-flex items-center bg-gradient-to-r from-blue-100 to-blue-200 text-blue-800 px-4 py-2 rounded-full text-sm font-medium">
                <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M9 19l3 3m0 0l3-3m-3 3V10"></path>
                </svg>
                Cloud Technologies
              </span>
              <span class="inline-flex items-center bg-gradient-to-r from-green-100 to-green-200 text-green-800 px-4 py-2 rounded-full text-sm font-medium">
                <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path>
                </svg>
                Containerization
              </span>
              <span class="inline-flex items-center bg-gradient-to-r from-purple-100 to-purple-200 text-purple-800 px-4 py-2 rounded-full text-sm font-medium">
                <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path>
                </svg>
                Distributed Systems
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>