<template>
  <section id="about" class="py-16 px-4 bg-gray-800">
    <div class="container mx-auto text-white">
      <h2 class="text-4xl font-bold text-center">About Me</h2>
      <p class="mt-6 text-lg text-center max-w-3xl mx-auto leading-relaxed">
        I am a passionate software and mobile developer with experience in both web and mobile technologies. My expertise includes creating intuitive and functional applications using modern frameworks like Vue.js for web development and Flutter for mobile development. While my background includes some web development and design, my focus has been on developing practical solutions that meet user needs and solve real-world problems.
      </p>
      <p class="mt-6 text-lg text-center max-w-3xl mx-auto leading-relaxed">
        I enjoy tackling complex challenges and turning ideas into effective, user-friendly applications. My approach is centered around delivering high-quality solutions and working collaboratively within Agile teams to ensure project success and client satisfaction.
      </p>
      <div class="mt-12 text-center">
        <h3 class="text-3xl font-semibold">Skills</h3>
        <ul class="list-none mt-4 inline-block text-left space-y-2">
          <li class="text-lg">JavaScript, Vue.js, Python, Flutter, Dart</li>
          <li class="text-lg">HTML, CSS, Tailwind CSS</li>
          <li class="text-lg">Mobile Development, Agile, Team Player</li>
        </ul>
      </div>
      <div class="mt-12 text-center">
        <h3 class="text-3xl font-semibold">Connect with Me</h3>
        <div class="mt-6 flex justify-center space-x-6">
          <!-- Replace the href with your actual social media links -->
          <a href="https://github.com/hilmanhaikal" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors duration-300">
            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 2a10 10 0 00-3.16 19.47c.5.09.68-.22.68-.48 0-.23-.01-.85-.01-1.67-2.78.6-3.37-1.34-3.37-1.34-.45-1.14-1.1-1.44-1.1-1.44-.9-.62.07-.61.07-.61 1 .07 1.53 1.03 1.53 1.03.9 1.53 2.36 1.09 2.94.83.09-.65.35-1.09.63-1.34-2.22-.25-4.56-1.11-4.56-4.95 0-1.09.39-1.98 1.03-2.68-.1-.25-.45-1.27.1-2.64 0 0 .84-.27 2.75 1.02a9.57 9.57 0 015 0c1.91-1.29 2.75-1.02 2.75-1.02.55 1.37.2 2.39.1 2.64.64.7 1.03 1.59 1.03 2.68 0 3.85-2.34 4.7-4.57 4.95.36.31.67.92.67 1.86 0 1.34-.01 2.42-.01 2.75 0 .27.18.59.69.49A10 10 0 0012 2z"/>
            </svg>
          </a>
          <a href="https://linkedin.com/in/hilmanhaikal" target="_blank" rel="noopener noreferrer" class="text-gray-400 hover:text-white transition-colors duration-300">
            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
              <path d="M19 0H5C2.25 0 0 2.25 0 5v14c0 2.75 2.25 5 5 5h14c2.75 0 5-2.25 5-5V5c0-2.75-2.25-5-5-5zm-9.75 17H6v-7h3.25v7zM7.5 8.75C6.34 8.75 5.5 7.91 5.5 6.75S6.34 4.75 7.5 4.75 9.5 5.59 9.5 6.75 8.66 8.75 7.5 8.75zm11.25 8.25h-3.25v-3.5c0-.83-.02-1.9-1.15-1.9-1.15 0-1.32.9-1.32 1.83v3.57H10.5v-7h3.13v.96h.04c.44-.84 1.52-1.7 3.12-1.7 3.33 0 3.95 2.19 3.95 5.04v2.7z"/>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutMe',
};
</script>

<style scoped>
section {
  padding: 4rem 0;
}
h2 {
  color: #ffffff;
}
p {
  color: #e5e7eb;
}
ul li {
  color: #d1d5db;
}
a {
  color: inherit;
}
svg {
  transition: color 0.3s ease-in-out;
}
</style>
