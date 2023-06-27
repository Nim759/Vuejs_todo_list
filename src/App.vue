<script setup>
import { RouterView } from "vue-router";
import Header from "./components/Header.vue";

// const props = defineProps(['foo'])
// console.log("++++++++++",props.foo)
</script>

<template>
  <Header />
  <RouterView />

</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500&family=Roboto&family=Roboto+Condensed:ital,wght@0,300;0,400;1,300&display=swap");
* {
  font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
