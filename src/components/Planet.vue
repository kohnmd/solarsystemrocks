<template>
    <h1>{{ planet.name }}</h1>
    <p>{{ planet.about }}</p>
    <img :src="planet.img" :alt="planet.name" class="big-ol-planet-pic">
</template>


<script>
export default {
    name: "Planet",
    props: ['planet'],
};
</script>