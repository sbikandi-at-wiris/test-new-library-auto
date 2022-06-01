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
  background: #42b983;
  color: #fff;
  cursor: pointer;
  border: 0;
  border-radius: 30px;
  padding: 1em 1.5em;
}
button:hover {
  background: #2f855a;
}
</style>
