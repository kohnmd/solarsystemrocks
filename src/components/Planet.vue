<template>
    <h1>{{ planet.name }}</h1>
    <p>{{ planet.about }}</p>
    <p>{{ planet.img }}</p>
</template>


<script>
export default {
    name: "Planet",
    props: ['planet'],
};
</script>