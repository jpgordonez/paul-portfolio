<template>
  <section id="home" class="min-h-screen flex items-center justify-center px-6">
    <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
      <!-- Left Content -->
      <div>
        <p class="text-gray-400 mb-3 tracking-widest uppercase text-sm">Welcome to my portfolio</p>

        <h1 class="text-5xl md:text-7xl font-bold leading-tight mb-6">
          Hi, I'm
          <span class="text-white">John Paul</span><br />
          <span class="text-gray-400">Web Developer</span>
        </h1>

        <p class="text-gray-400 text-lg leading-relaxed max-w-xl mb-8">
          I build modern websites using Vue, Tailwind CSS, Laravel, and clean UI design. Passionate
          in creating responsive and professional systems.
        </p>

        <div class="flex flex-wrap gap-4">
          <a
            href="#projects"
            class="px-6 py-3 rounded-full bg-white text-black font-semibold hover:scale-105 transition"
          >
            View Projects
          </a>

          <a
            href="#contact"
            class="px-6 py-3 rounded-full border border-white/20 hover:bg-white hover:text-black transition"
          >
            Contact Me
          </a>
        </div>
      </div>

      <!-- Right Content -->
      <div class="flex justify-center">
        <div
          class="w-72 h-72 md:w-96 md:h-96 rounded-full border border-white/10 shadow-2xl overflow-hidden"
        >
          <img src="/img/pic/john paul.jpeg" alt="John Paul" class="w-full h-full object-cover" />
        </div>
      </div>
    </div>
  </section>
</template>
