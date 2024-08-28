<template>
  <section id="projects" class="py-16 px-4 bg-stone-400">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center text-black">Projects</h2>
      <div class="grid grid-cols-1 gap-8 mt-8">
        <!-- Example Project -->
        <div class="p-6 rounded-lg shadow-md bg-stone-800">
          <h3 class="text-xl font-semibold text-white">MindGuard</h3>
          <p class="mt-2 text-white">A brief description of the project, technologies used, and key features.</p>
          <a href="#" class="mt-4 inline-block text-white hover:text-stone-500">View Project</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectList',
};
</script>

<style scoped>
section {
  padding: 4rem 0;
}
</style>
