<template>
  <section id="contact" class="section-padding bg-gradient-to-br from-white to-gray-50">
    <div class="container-max">
      <!-- Header dengan animasi -->
      <div class="text-center mb-20">
        <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-full mb-6">
          <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
          </svg>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-secondary-900 mb-6 bg-gradient-to-r from-primary-600 to-accent-600 bg-clip-text text-transparent">
          Let's Connect
        </h2>
        <p class="text-xl text-secondary-600 max-w-3xl mx-auto leading-relaxed">
          Ready to collaborate or discuss opportunities? 
          <span class="font-semibold text-primary-600">Let's build</span> something 
          <span class="font-semibold text-accent-600">amazing</span> together!
        </p>
      </div>

      <!-- Contact Cards Grid -->
      <div class="grid lg:grid-cols-3 gap-8 mb-16">
        <!-- Email Card -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-primary-500 to-accent-500"></div>
          <div class="flex items-start mb-6">
            <div class="w-14 h-14 bg-gradient-to-br from-primary-100 to-accent-100 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-7 h-7 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">Email</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-primary-500 to-accent-500 rounded-full"></div>
            </div>
          </div>
          <div class="space-y-4">
            <a href="mailto:ariwiraatmaja@gmail.com" class="flex items-center p-4 bg-gradient-to-r from-primary-50 to-accent-50 rounded-xl hover:shadow-md transition-all group">
              <div class="w-12 h-12 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm group-hover:scale-105 transition-transform">
                <svg class="w-6 h-6 text-primary-600" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-800">Email Me</div>
                <div class="text-sm text-gray-600">ariwiraatmaja@gmail.com</div>
              </div>
            </a>
          </div>
        </div>

        <!-- GitHub Card -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-gray-500 to-gray-700"></div>
          <div class="flex items-start mb-6">
            <div class="w-14 h-14 bg-gradient-to-br from-gray-100 to-gray-200 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-7 h-7 text-gray-700" fill="currentColor" viewBox="0 0 24 24">
                <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">GitHub</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-gray-500 to-gray-700 rounded-full"></div>
            </div>
          </div>
          <div class="space-y-4">
            <a href="https://github.com/ariwiraa" target="_blank" class="flex items-center p-4 bg-gradient-to-r from-gray-50 to-gray-100 rounded-xl hover:shadow-md transition-all group">
              <div class="w-12 h-12 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm group-hover:scale-105 transition-transform">
                <svg class="w-6 h-6 text-gray-700" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-800">View Projects</div>
                <div class="text-sm text-gray-600">github.com/ariwiraa</div>
              </div>
            </a>
          </div>
        </div>

        <!-- LinkedIn Card -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-blue-500 to-blue-700"></div>
          <div class="flex items-start mb-6">
            <div class="w-14 h-14 bg-gradient-to-br from-blue-100 to-blue-200 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-7 h-7 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">LinkedIn</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-blue-500 to-blue-700 rounded-full"></div>
            </div>
          </div>
          <div class="space-y-4">
            <a href="https://linkedin.com/in/ari-wira-atmaja" target="_blank" class="flex items-center p-4 bg-gradient-to-r from-blue-50 to-blue-100 rounded-xl hover:shadow-md transition-all group">
              <div class="w-12 h-12 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm group-hover:scale-105 transition-transform">
                <svg class="w-6 h-6 text-blue-600" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                </svg>
              </div>
              <div>
                <div class="font-semibold text-gray-800">Connect</div>
                <div class="text-sm text-gray-600">Ari Wira Atmaja</div>
              </div>
            </a>
          </div>
        </div>
      </div>

      <!-- Call to Action -->
      <div class="text-center">
        <div class="card max-w-2xl mx-auto bg-gradient-to-r from-primary-50 to-accent-50 border-2 border-primary-100">
          <div class="flex items-center justify-center mb-6">
            <div class="w-16 h-16 bg-gradient-to-br from-primary-500 to-accent-500 rounded-full flex items-center justify-center">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a2 2 0 01-2-2v-6a2 2 0 012-2h8z"></path>
              </svg>
            </div>
          </div>
          <h3 class="text-2xl font-bold text-secondary-900 mb-4">Ready to Start a Project?</h3>
          <p class="text-secondary-600 mb-6 leading-relaxed">
            I'm always interested in new opportunities and collaborations. 
            Whether you have a project in mind or just want to connect, I'd love to hear from you!
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <a href="mailto:ariwiraatmaja@gmail.com" class="btn-primary inline-flex items-center justify-center">
              <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
              </svg>
              Send Email
            </a>
            <a href="/CV_20250708.pdf" target="_blank" class="btn-secondary inline-flex items-center justify-center">
              <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
              </svg>
              Download Resume
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>