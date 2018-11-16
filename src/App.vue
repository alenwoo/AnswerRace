<template>
  <div id="app">
    <login></login>
    <!-- <home></home> -->
  </div>
</template>

<script>
import login from "./components/login";
import HelloWorldVue from "./components/HelloWorld.vue";
export default {
  name: "App",
  components: {
    login: login,
    home: HelloWorldVue
  },
  methods: {}
};
</script>

<style>
</style>
