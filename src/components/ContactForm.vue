<template>
  <section id="contact" class="py-16 px-4 bg-stone-400">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center text-black">Contact Me</h2>
      <form class="mt-8 max-w-lg mx-auto">
        <div class="mb-4">
          <label for="name" class="block text-sm font-medium mb-2 text-black">Name</label>
          <input id="name" type="text" class="w-full border border-gray-300 rounded-md p-2" required />
        </div>
        <div class="mb-4">
          <label for="email" class="block text-sm font-medium mb-2 text-black">Email</label>
          <input id="email" type="email" class="w-full border border-gray-300 rounded-md p-2" required />
        </div>
        <div class="mb-4">
          <label for="message" class="block text-sm font-medium mb-2 text-black">Message</label>
          <textarea id="message" rows="4" class="w-full border border-gray-300 rounded-md p-2" required></textarea>
        </div>
        <button type="submit" class="bg-stone-800 text-white hover:text-stone-400 px-4 py-2 rounded-md">Send Message</button>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ContactForm',
};
</script>

<style scoped>
section {
  padding: 4rem 0;
}
</style>
