<template>
  <div class="about">
    <h1>About Me</h1>
  </div>

  <!-- <container>
    <img
      src="../../src/assets/img/gnocchiandpaul.jpg"
      alt="Family"
      class="pic-1"
    />
  </container>
  <container>
    <img
      src="../../src/assets/img/emilyandpaul.jpg"
      alt="Family"
      class="pic-2"
    />
  </container>
  <container>
    <img
      src="../../src/assets/img/oliveandpaul.jpg"
      alt="Family"
      class="pic-3"
    />
  </container> -->
  <section>
    <p class="about-p1">
      My name is Steven (Paul) Ijames-last name pronounced "Ims". I entered
      Univerty of Denver's Coding Bootcamp during June of 20' and graduated with
      a certification in Full Stack Web Development. While I started my
      education not knowing much about HTML, CSS, and JavaScript I found awesome
      tutors who pushed me to understand concepts that were beyond my scope and
      now easier to engage with and implement within my code.
    </p>
    <p class="about-p2">
      Since graduating I felt the need to sharpen up my skills by diving deeper
      into JavaScript and learning frameworks such as React.js and Vue.js. I
      really have enjoyed learning Vue.js, Vue-Cli, Vue Router, Attribute
      Binding and creating custom reuseable Components. Knowing how Vue manages
      the DOM behind the scenes, doing the heavy lifting, has given me more
      possibilites to enact in a shorter amount of time.
    </p>
    <p class="about-p3">
      I have been a career musician (Pianist & DJ) for most of my life and
      understand the need for "practice makes perfect". With these same practice
      concepts I have applied them to web development and continue to learn each
      and every day.
    </p>
    <p class="about-p4">
      Some of favorite past-times are creating web apps, composing, spending
      time with my wife, two kids and friends, music production and aviation.
      For certain, I am a foodie at heart and especially love Pho, Italian,
      Mexican and craft drinks.
    </p>
    <div class="custom">{{ count }} {{ message }}</div>
  </section>
</template>

<script>
export default {
  data: () => ({
    count: 0,
    message: "I am mastering Vue",
  }),
};
</script>

<style scoped>
img {
  width: 100%;
  height: auto;
  border-radius: 50%;
  border: solid 1px;
  border-color: gray;
  margin: 10px;
}

.container {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

@media (min-width: 550px) {
  .container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
  }
}
</style>
