<template>
  <div id="app" class="bg-gray-50 text-gray-800 ">
    <MainHeader />
    <main>
      <HeroSection />
      <ProjectList />
      <AboutMe />
      <ContactForm />
    </main>
    <SiteFooter />
  </div>
</template>

<script>
import MainHeader from './components/MainHeader.vue';
import HeroSection from './components/HeroSection.vue';
import ProjectList from './components/ProjectList.vue';
import AboutMe from './components/AboutMe.vue';
import ContactForm from './components/ContactForm.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'App',
  components: {
    MainHeader,
    HeroSection,
    ProjectList,
    AboutMe,
    ContactForm,
    SiteFooter,
  },
};
</script>

<style>
html {
  scroll-behavior: smooth;
}

body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  margin: 0;
  padding: 0;
}
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
main {
  flex: 1;
}
</style>
