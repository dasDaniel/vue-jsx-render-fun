<template>
  <div id="app">
    <MyComponent />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import MyComponent from "./MyComponent.vue";

export default Vue.extend({
  name: "App",
  components: {
    MyComponent,
  },
});
</script>
