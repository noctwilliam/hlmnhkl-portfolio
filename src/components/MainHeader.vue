<template>
  <header class="bg-black shadow-sm py-4 rounded">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
      <h1 class="text-2xl font-semibold text-white">hlmnhkl</h1>
      <nav>
        <ul class="flex flex-wrap space-x-4 mt-2 lg:mt-0">
          <li><a href="#hero" class="hover:text-stone-500">Home</a></li>
          <li><a href="#projects" class="hover:text-stone-500">Projects</a></li>
          <li><a href="#about" class="hover:text-stone-500">About</a></li>
          <li><a href="#contact" class="hover:text-stone-500">Contact</a></li>
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
  background-color: #292524;
}
a {
  text-decoration: none;
}
li {
  color: #ffffff;
}
</style>
