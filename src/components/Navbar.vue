<template>
  <header class="sticky top-0 z-50 backdrop-blur-md bg-black/70 border-b border-white/10">
    <nav class="max-w-6xl mx-auto px-6 py-4 flex items-center justify-between">
      <!-- Logo -->
      <div class="text-xl font-bold tracking-wide">
        <span class="text-white">Paul</span>
        <span class="text-gray-400">Portfolio</span>
      </div>

      <!-- Desktop Menu -->
      <ul class="hidden md:flex items-center gap-8 text-sm font-medium">
        <li>
          <a href="#home" class="hover:text-gray-300 transition">Home</a>
        </li>
        <li>
          <a href="#about" class="hover:text-gray-300 transition">About</a>
        </li>
        <li>
          <a href="#projects" class="hover:text-gray-300 transition">Projects</a>
        </li>
        <li>
          <a href="#skills" class="hover:text-gray-300 transition">Skills</a>
        </li>
        <li>
          <a href="#contact" class="hover:text-gray-300 transition">Contact</a>
        </li>
      </ul>

      <!-- Button -->
      <a
        href="#contact"
        class="hidden md:inline-block px-5 py-2 rounded-full bg-white text-black font-semibold hover:scale-105 transition"
      >
        Hire Me
      </a>

      <!-- Mobile Icon -->
      <button class="md:hidden text-2xl">☰</button>
    </nav>
  </header>
</template>
