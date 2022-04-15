<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/panda_logo.png" />
    <HelloWorld msg="Welcome to Bamboo Toothbrush Store" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
