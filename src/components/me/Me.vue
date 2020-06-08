<template>
  <div>
    <h2>It started out here...</h2>
    <img src="./me.png" alt="pay the internet company, man" />
    <p>
      From
      <b>Madrid, Spain</b>
      equiped with
      <b>
        Spanish (Native)
        English (Professional)
        Japanese (Basic)
      </b>
      always available in
      <b>+34 616 32 14 50</b>
      and
    </p>
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
p {
  text-align: justify;
}
ul {
  text-align: left;
}
</style>
