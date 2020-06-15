<template>
    <div class="md:w-1/5 bg-white shadow-2xl rounded-lg h-full m-4 p-6">
        <h2 class="text-3xl bg-pink-500 text-white rounded-lg">Who</h2>
        <div>
            <img class="rounded-lg my-4" src="./me.jpg" alt="pay the internet company, man" />
        </div>
        <pre>
From
<b>Madrid, Spain</b>
equiped with
<b>
Spanish (Native)
English (B2+)
Japanese (Basic)
</b>
always available in
<b>+34 616 32 14 50</b>
        </pre>
    </div>
</template>

<script>
export default {
    name: "me",
    props: {
        msg: String
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
    width: 100%;
}
</style>
