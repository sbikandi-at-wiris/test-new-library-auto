<template>
  <button>{{ label }}</button>
</template>

<script>
export default {
  name: "AButton",
  props: {
    label: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped>
button {
  background: #b9427d;
  color: #fff;
  cursor: pointer;
  border: 0;
  border-radius: 30px;
  padding: 1em 1.5em;
}
button:hover {
  background: #852f5e;
}
</style>
