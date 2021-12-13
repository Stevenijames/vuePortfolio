<template>
  <div class="projects">
    <h2>Projects</h2>
  </div>
  <section class="card1">
    <p class="title">Project1</p>
  </section>
  <section class="card1">
    <p class="title">Project2</p>
  </section>
  <section class="card1">
    <p class="title">Project3</p>
  </section>
  <section class="card2">
    <p class="title">Project4</p>
  </section>
  <section class="card2">
    <p class="title">Project5</p>
  </section>
  <section class="card2">
    <p class="title">Project6</p>
  </section>
</template>

<script>
export default {};
</script>

<style>
.card1,
.card2 {
  display: flex;
  flex-direction: row;
  flex-flow: wrap;
}
</style>
