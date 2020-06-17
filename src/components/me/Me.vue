<template>
    <div class="md:w-1/5 bg-white shadow-2xl rounded-lg h-full m-4 py-6 px-10">
        <h1 class="text-4xl">Who</h1>
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
