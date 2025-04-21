<template>
  <button class="my-button"><slot /></button>
</template>

<script>
export default {
  name: "MyButton",
};
</script>

<style>
.my-button {
  padding: 0.5em 1em;
  border: 1px solid #ccc;
}
</style>
