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
      this.$emit("btn-click");
    },
  },
};
</script>

<style></style>
