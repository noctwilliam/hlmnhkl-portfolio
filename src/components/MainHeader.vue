<template>
  <header class="bg-white shadow-sm py-4">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
      <h1 class="text-2xl font-semibold">hlmnhkl</h1>
      <nav>
        <ul class="flex flex-wrap space-x-4 mt-2 lg:mt-0">
          <li><a href="#hero" class="hover:text-blue-600">Home</a></li>
          <li><a href="#projects" class="hover:text-blue-600">Projects</a></li>
          <li><a href="#about" class="hover:text-blue-600">About</a></li>
          <li><a href="#contact" class="hover:text-blue-600">Contact</a></li>
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
  background-color: #fff;
}
a {
  text-decoration: none;
}
</style>
