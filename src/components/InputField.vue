<template>
  <div>
    <input
      type="text"
      :placeholder="placeholder"
      id="letterInput"
      :style="{
        border: color,
        padding: '10px',
        width: '30%',
        borderRadius: '10px',
      }"
    />
  </div>
</template>

<script>
export default {
  name: "InputField",
  props: {
    placeholder: {
      type: String,
      default: "",
    },
    color: {
      type: String,
      default: "",
    },
  },
};
</script>

<style>
</style>