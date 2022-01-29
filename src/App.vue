<template>
    <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link> | 
        <router-link to="/random">Random</router-link>
    </div>
    <h1>Solar System Rocks</h1>
    <router-view />
</template>

<style>
@import "./assets/styles/style.css";
</style>
