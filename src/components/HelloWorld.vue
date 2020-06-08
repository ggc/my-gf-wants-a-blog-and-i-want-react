<template>
  <div class="page">
    <div class="main">
      <div class="me">
        <me></me>
        <div class="sideskills">
          <sideskills></sideskills>
        </div>
      </div>

      <div class="experience">
        <h2>and now...</h2>
        <experience></experience>
      </div>

      <!-- <h1>{{ msg }}</h1> -->
    </div>
    <div class="other">
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
.page {
}
.main {
  display: flex;
}
.me {
  max-width: 20%;
  border: 1px solid black;
  padding: 1em;
  margin: 2%;
  border-radius: 2em;
}
.sideskills {
  /* width: 13%; */
  border: 1px solid black;
  margin: 2%;
  border-radius: 2em;
}
.experience {
  width: 65%;
  border: 1px solid black;
  margin: 2%;
  border-radius: 2em;
}
.other {
  margin: 2em;
  border-radius: 2em;
  border: 1px solid black;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
