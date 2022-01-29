<template>
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

#app {
    text-align: center;
    margin-top: 60px;
}
</style>
