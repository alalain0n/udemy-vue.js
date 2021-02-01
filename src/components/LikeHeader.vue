<template>
  <div>
    <slot></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        firstName: "Jack",
        lastName: "Donald",
      },
    };
  },
};
</script>

<style>
div {
  border: 1px solid blue;
}

h1 {
  color: red;
}
</style>