<template>
  <section id="contact" class="outline outline-1 outline-offset-0 outline-gray-300 py-16 px-4 bg-gray-700">
    <div class="container mx-auto text-white">
      <h2 class="text-3xl font-bold text-center">Contact Me</h2>
      <form class="mt-8 max-w-lg mx-auto">
        <div class="mb-4">
          <label for="name" class="block text-sm font-medium mb-2">Name</label>
          <input id="name" type="text" class="w-full border border-gray-300 rounded-md p-2" required />
        </div>
        <div class="mb-4">
          <label for="email" class="block text-sm font-medium mb-2">Email</label>
          <input id="email" type="email" class="w-full border border-gray-300 rounded-md p-2" required />
        </div>
        <div class="mb-4">
          <label for="message" class="block text-sm font-medium mb-2">Message</label>
          <textarea id="message" rows="4" class="w-full border border-gray-300 rounded-md p-2" required></textarea>
        </div>
        <button type="submit" class="hover:bg-gray-300 hover:text-gray-950 inline-block bg-gray-950 text-white py-2 px-4 rounded-lg">Send Message</button>
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
