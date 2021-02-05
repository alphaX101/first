
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/lf.jpg" />
    <HelloWorld msg="Welcome to my App index" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

<style lang="sass" scoped>
img
  width: 300px
</style>