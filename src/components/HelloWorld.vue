<template>
    <div class="page">
        <div class="main md:flex">
            <me></me>

            <experience></experience>

            <sideskills></sideskills>
            <!-- <h1>{{ msg }}</h1> -->
        </div>

        <div class="bg-white rounded-lg shadow-2xl m-4 py-6 px-10">
            <p>
                When he's not making
                <i>this</i>
                he's in
            </p>
            <br />
            <span
                v-for="item in hobbies"
                :key="item"
                class="shadow-md text-color-green-900 bg-green-400 rounded-full px-4 py-2 m-1"
            >
                <b>{{ item }}</b>
            </span>
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
    data: function() {
        return {
            hobbies: [
                "3d printing 3d design",
                "IoT",
                "Biking",
                "Playing guitar",
                "Sociology",
                "Artificial intelligence",
                "Puzzles (Rubik's cube, puzzles, riddles)"
            ]
        };
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
