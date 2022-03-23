<template>
  <button>{{ title }}</button>
</template>

<script lang="ts">
import { defineComponent } from "vue";
/* eslint-disable vue/multi-word-component-names */
export default defineComponent({
  name: "Button",
  props: {
    title: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
