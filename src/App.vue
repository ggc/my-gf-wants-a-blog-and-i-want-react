<template>
    <div id="app">
        <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
        <h1>Looking for a software developer?</h1>
        <h2>Here's Gabriel Galan Casillas and what he did</h2>
        <a href="mailto:gabriel.galancasillas@outlook.com">mail</a>
        <br />
        <a href="https://www.linkedin.com/in/gabrielgalancasillas/">linkedin</a>
        <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
    name: "App",
    components: {
        HelloWorld
    }
};
</script>

<style>
@font-face {
    font-family: comfortaa;
    src: url("./assets/Comfortaa.ttf");
}

html {
    background: linear-gradient(34deg, #0c94f9 0%, #1ab2f9 100%);
}
* {
    font-family: comfortaa;
}
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
