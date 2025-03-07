<script>
  import AppHeader from "@/components/AppHeader.vue";
 import ContactForm from "./components/ContactForm.vue";

  export default {
    components: {
      AppHeader,
      ContactForm,
    },
  }
</script>

<template>
  <!-- <h1>Hello, Vue.js!</h1> -->
  <div id="app">
    <AppHeader />
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>

<style>
  .page {
    max-width: 400px;
    margin: auto;
  }
</style>