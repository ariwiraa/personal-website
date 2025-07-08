<template>
  <section id="skills" class="section-padding bg-gradient-to-br from-white to-gray-50">
    <div class="container-max">
      <!-- Header dengan animasi -->
      <div class="text-center mb-20">
        <div class="inline-flex items-center justify-center w-16 h-16 bg-primary-100 rounded-full mb-6">
          <svg class="w-8 h-8 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
          </svg>
        </div>
        <h2 class="text-4xl md:text-5xl font-bold text-secondary-900 mb-6 bg-gradient-to-r from-primary-600 to-accent-600 bg-clip-text text-transparent">
          Technical Skills
        </h2>
        <p class="text-xl text-secondary-600 max-w-3xl mx-auto leading-relaxed">
          Technologies and tools I work with to build 
          <span class="font-semibold text-primary-600">efficient</span> and 
          <span class="font-semibold text-accent-600">scalable</span> backend solutions
        </p>
      </div>

      <!-- Skills Grid -->
      <div class="grid lg:grid-cols-3 gap-8 mb-16">
        <!-- Backend Languages -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-primary-500 to-accent-500"></div>
          <div class="flex items-start mb-6">
            <div class="w-14 h-14 bg-gradient-to-br from-primary-100 to-accent-100 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-7 h-7 text-primary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">Backend Languages</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-primary-500 to-accent-500 rounded-full"></div>
            </div>
          </div>
          <div class="space-y-4">
            <!-- Java -->
            <div class="flex items-center p-3 bg-gradient-to-r from-orange-50 to-red-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/java.svg" alt="Java" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">Java</div>
                <div class="text-sm text-gray-600">Enterprise Backend Development</div>
              </div>
            </div>
            <!-- Go -->
            <div class="flex items-center p-3 bg-gradient-to-r from-cyan-50 to-blue-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/go.svg" alt="Go" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">Go</div>
                <div class="text-sm text-gray-600">High-Performance APIs</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Frameworks -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-accent-500 to-secondary-500"></div>
          <div class="flex items-start mb-6">
            <div class="w-14 h-14 bg-gradient-to-br from-accent-100 to-secondary-100 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-7 h-7 text-accent-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">Frameworks</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-accent-500 to-secondary-500 rounded-full"></div>
            </div>
          </div>
          <div class="space-y-4">
            <!-- Spring Boot -->
            <div class="flex items-center p-3 bg-gradient-to-r from-green-50 to-emerald-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/springboot.svg" alt="Spring Boot" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">Spring Boot</div>
                <div class="text-sm text-gray-600">Java Enterprise Framework</div>
              </div>
            </div>
            <!-- Gin -->
            <div class="flex items-center p-3 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/gin.svg" alt="Gin" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">Gin</div>
                <div class="text-sm text-gray-600">Go Web Framework</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Databases & Tools -->
        <div class="card group hover:shadow-2xl hover:-translate-y-2 transition-all duration-300 relative overflow-hidden">
          <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-secondary-500 to-primary-500"></div>
          <div class="flex items-start mb-6">
            <div class="w-14 h-14 bg-gradient-to-br from-secondary-100 to-primary-100 rounded-2xl flex items-center justify-center mr-4 group-hover:scale-110 transition-transform">
              <svg class="w-7 h-7 text-secondary-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"></path>
              </svg>
            </div>
            <div>
              <h3 class="text-2xl font-bold text-secondary-900 mb-2">Databases & Tools</h3>
              <div class="w-16 h-1 bg-gradient-to-r from-secondary-500 to-primary-500 rounded-full"></div>
            </div>
          </div>
          <div class="space-y-4">
            <!-- PostgreSQL -->
            <div class="flex items-center p-3 bg-gradient-to-r from-blue-50 to-cyan-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/postgresql.svg" alt="PostgreSQL" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">PostgreSQL</div>
                <div class="text-sm text-gray-600">Advanced Relational Database</div>
              </div>
            </div>
            <!-- MySQL -->
            <div class="flex items-center p-3 bg-gradient-to-r from-orange-50 to-yellow-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/mysql.svg" alt="MySQL" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">MySQL</div>
                <div class="text-sm text-gray-600">Popular SQL Database</div>
              </div>
            </div>
            <!-- Git -->
            <div class="flex items-center p-3 bg-gradient-to-r from-red-50 to-pink-50 rounded-xl hover:shadow-md transition-all">
              <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center mr-4 shadow-sm">
                <img src="/images/git.svg" alt="Git" class="w-6 h-6" />
              </div>
              <div>
                <div class="font-semibold text-gray-800">Git</div>
                <div class="text-sm text-gray-600">Version Control System</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SkillsSection'
}
</script>