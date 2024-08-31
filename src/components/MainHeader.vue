<template>
  <header class="shadow-sm py-4 bg-gray-900">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
      <h1 class="tracking-wide text-2xl font-semibold text-white">hlmnhkl</h1>
      <!-- Modern Burger Icon (visible on mobile) -->
      <div class="lg:hidden">
        <button @click="isMenuOpen = !isMenuOpen" class="text-white focus:outline-none">
          <svg
            :class="{'transform rotate-90': isMenuOpen}" 
            class="w-8 h-8 transition-transform duration-300 ease-in-out" 
            fill="none" 
            stroke="currentColor" 
            viewBox="0 0 24 24" 
            xmlns="http://www.w3.org/2000/svg"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
          </svg>
        </button>
      </div>
      <!-- Navigation Menu -->
      <nav 
        :class="{'block': isMenuOpen, 'hidden': !isMenuOpen}" 
        class="w-full lg:w-auto lg:flex lg:items-center transition-all duration-300 ease-in-out"
      >
        <ul class="flex flex-col lg:flex-row lg:space-x-8 mt-4 lg:mt-0">
          <li><a href="#hero" class="hover:text-indigo-400 transition-colors duration-200 text-lg block lg:inline-block mt-2 lg:mt-0">Home</a></li>
          <li><a href="#projects" class="hover:text-indigo-400 transition-colors duration-200 text-lg block lg:inline-block mt-2 lg:mt-0">Projects</a></li>
          <li><a href="#about" class="hover:text-indigo-400 transition-colors duration-200 text-lg block lg:inline-block mt-2 lg:mt-0">About</a></li>
          <li><a href="#contact" class="hover:text-indigo-400 transition-colors duration-200 text-lg block lg:inline-block mt-2 lg:mt-0">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'MainHeader',
  data() {
    return {
      isMenuOpen: false, // State to toggle the menu
    };
  },
};
</script>

<style scoped>
header {
  background-color: rgb(17 24 39);
}
a {
  text-decoration: none;
}
li {
  color: #ffffff;
}
</style>
