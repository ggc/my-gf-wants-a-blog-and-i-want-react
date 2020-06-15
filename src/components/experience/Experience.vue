<template>
    <div class="md:w-3/5 bg-white rounded-lg shadow-2xl m-4 p-8 text-left">
        <p class="text-4xl">and now...</p>

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
