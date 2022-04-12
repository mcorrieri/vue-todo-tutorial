<template>
  <button @click="handleClick()" :style="{ background: color }" class="btn">
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "TheButton",
  props: {
    text: String,
    color: String,
  },
  methods: {
    handleClick() {
      console.log("hey hotdog man");
    },
  },
};
</script>

<style></style>
