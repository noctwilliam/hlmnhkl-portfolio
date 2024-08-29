<template>
  <header class="shadow-sm py-4">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
      <h1 class="tracking-wide text-2xl font-semibold text-white">hlmnhkl</h1>
      <nav>
        <ul class="flex flex-wrap space-x-4 mt-2 lg:mt-0 gap-2">
          <li><a href="#hero" class="hover:text-gray-300">Home</a></li>
          <li><a href="#projects" class="hover:text-gray-300">Projects</a></li>
          <li><a href="#about" class="hover:text-gray-300">About</a></li>
          <li><a href="#contact" class="hover:text-gray-300">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'MainHeader',
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
