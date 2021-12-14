<template>
  <h4>Current Projects</h4>
  <section class="card">
    <img
      src="../../src/assets/img/find-a-word-logo-white.png"
      alt="Find A Word Vue App"
    />
    <p class="text">
      <a href="">Find A Word<br /><em>Axios Call</em></a>
    </p>
  </section>
  <section class="card">
    <img src="../../src/assets/img/worthyOrigin.png" alt="Worthy Origin" />
    <p class="text">
      <a href="https://worthy-origin.herokuapp.com/">Worthy Origin</a>
    </p>
  </section>
</template>

<script>
export default {
  name: "Projects",
};
</script>

<style scoped>
img {
  width: 22%;
  height: 25vh;
  object-fit: cover;
  border: solid gray 3px;
  margin-bottom: 10px;
  margin-top: 10px;
}
section {
  box-sizing: content-box;
  border: solid grey 2.5px;
  margin-top: 10px;
  padding: 10px;
}
</style>
