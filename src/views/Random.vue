<template>
    <div class="random">
        <h2>Random shit</h2>
    </div>

    <SolarSystem />
</template>

<script>
import SolarSystem from "@/components/SolarSystem.vue";

export default {
    name: "Random",
    components: {
        SolarSystem,
    },
};
</script>