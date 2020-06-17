<template>
    <div class="md:w-3/5 bg-white rounded-lg shadow-2xl m-4 py-6 px-10 text-left">
        <h1 class="text-4xl text-center">What</h1>

        <kairos></kairos>
        <tenea></tenea>
        <telefonica></telefonica>
    </div>
</template>

<script>
import Kairos from "./Kairos";
import Tenea from "./Tenea";
import Telefonica from "./Telefonica";

export default {
    name: "experience",
    props: {
        msg: String
    },
    components: {
        Kairos,
        Tenea,
        Telefonica
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
