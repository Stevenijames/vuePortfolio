<template>
  <div class="home">
    <div>
      <button @click="showImage = !showImage">Toggle Image</button>
    </div>
    <transition
      enter-active-class="animate__animated animate__fadeIn"
      leave-active-class="animate__animated animate__fadeOut"
    >
      <img
        v-if="showImage"
        alt="coding languages logo"
        src="../assets/img/codingLanguages2.png"
        class="logo"
      />
    </transition>
    <Greeting msg="Welcome to Paul's Vue App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Greeting from "@/components/Greeting.vue";

export default {
  name: "Home",
  components: {
    Greeting,
  },
  data: () => ({
    showImage: true,
  }),
};
</script>

<style scoped>
.logo {
  width: 30vw;
  height: auto;
}
</style>
