<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
  <SolarSystem />
</template>

<script>
import SolarSystem from "./components/SolarSystem.vue";

export default {
    name: "App",
    components: {
        SolarSystem
    },
};
</script>

<style>
@import './assets/styles/style.css';
</style>
