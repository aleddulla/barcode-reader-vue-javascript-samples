<template>
  <div id="app">
    <HelloWorld />
  </div>
</template>

<script>
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld,
  },
});
</script>
