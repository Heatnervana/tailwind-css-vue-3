<template>
  <div class="min-h-screen bg-gray-50 text-gray-800">
    <!-- Navbar -->
    <nav class="flex justify-between items-center px-8 py-4 bg-white shadow">
      <div class="text-2xl font-bold text-blue-600">My Portfolio</div>
      <ul class="flex space-x-6">
        <li><a href="#about" class="hover:text-blue-500">About</a></li>
        <li><a href="#projects" class="hover:text-blue-500">Projects</a></li>
        <li><a href="#experience" class="hover:text-blue-500">Experience</a></li>
        <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
      </ul>
    </nav>

    <!-- Hero Section -->
    <section class="flex flex-col items-center justify-center py-16 bg-gradient-to-r from-blue-100 to-blue-300">
      <h1 class="text-4xl font-extrabold mb-4">Welcome to My Landing Page</h1>
      <p class="text-lg text-gray-700 mb-6">Showcasing my work, experience, and how to contact me.</p>
      <a href="#contact" class="px-6 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 transition">Get in Touch</a>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 px-8 max-w-3xl mx-auto">
      <h2 class="text-3xl font-bold mb-4">About Me</h2>
      <p class="text-gray-700">I am a passionate developer with experience in building modern web applications using Vue.js and Tailwind CSS.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 px-8 bg-white max-w-4xl mx-auto">
      <h2 class="text-3xl font-bold mb-4">Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="bg-blue-50 p-6 rounded shadow">
          <h3 class="font-semibold text-xl mb-2">Project One</h3>
          <p class="text-gray-700">A cool project built with Vue and Tailwind CSS.</p>
        </div>
        <div class="bg-blue-50 p-6 rounded shadow">
          <h3 class="font-semibold text-xl mb-2">Project Two</h3>
          <p class="text-gray-700">Another awesome project showcasing my skills.</p>
        </div>
      </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-16 px-8 max-w-3xl mx-auto">
      <h2 class="text-3xl font-bold mb-4">Experience</h2>
      <ul class="space-y-4">
        <li>
          <span class="font-semibold">Frontend Developer</span> at TechCorp (2022–2024)
          <p class="text-gray-700">Worked on building scalable web apps using Vue.js.</p>
        </li>
        <li>
          <span class="font-semibold">UI Designer</span> at DesignStudio (2020–2022)
          <p class="text-gray-700">Designed user interfaces with a focus on usability and aesthetics.</p>
        </li>
      </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 px-8 bg-blue-50 max-w-3xl mx-auto rounded">
      <h2 class="text-3xl font-bold mb-4">Contact</h2>
      <form class="flex flex-col space-y-4">
        <input type="text" placeholder="Your Name" class="p-3 rounded border border-gray-300" />
        <input type="email" placeholder="Your Email" class="p-3 rounded border border-gray-300" />
        <textarea placeholder="Your Message" class="p-3 rounded border border-gray-300"></textarea>
        <button type="submit" class="px-6 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 transition">Send</button>
      </form>
    </section>
  </div>
</template>

<script setup>
// No script needed for static layout
</script>

<style>
/* You can add custom styles here if needed */
</style>