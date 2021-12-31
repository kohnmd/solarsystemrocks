<template>
    hello sol
    <Planet
        v-for="planet in planets"
        v-bind:planet="planet"
        v-bind:key="planet.id"
    />
</template>

<script>
import Planet from "./Planet.vue";

export default {
    name: "SolarSystem",
    components: {
        Planet,
    },
    data() {
        return {
            planets: [
                {id: 1, name: "Mercury", about: "Smallest of them all!", img: "[mercury image]"},
                {id: 2, name: "Venus", about: "Sooooo hot", img: "[v image]"},
                {id: 3, name: "Earth", about: "You Are Here", img: "[blue marble]"},
            ]
        }
    }
};
</script>
