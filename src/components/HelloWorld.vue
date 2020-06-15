<template>
    <div class="page">
        <div class="main md:flex">
            <me></me>

            <experience></experience>

            <sideskills></sideskills>
            <!-- <h1>{{ msg }}</h1> -->
        </div>

        <div class="bg-white rounded-lg shadow-2xl m-4">
            when he's not making
            <i>this</i> he's in
            <b>
                <ul>
                    <li>3d printing 3d design</li>
                    <li>IoT</li>
                    <li>Biking</li>
                    <li>Playing guitar</li>
                    <li>Sociology</li>
                    <li>Artificial intelligence</li>
                    <li>Puzzles (Rubik's cube, puzzles, riddles)</li>
                </ul>
            </b>
        </div>
    </div>
</template>

<script>
import Experience from "./experience/Experience";
import Me from "./me/Me";
import Sideskills from "./sideskills/Sideskills";

export default {
    name: "HelloWorld",
    props: {
        msg: String
    },
    components: {
        Experience,
        Me,
        Sideskills
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
