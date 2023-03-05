<template>
  <div>
    <p>User is premium: {{ premium }}</p>
  </div>
</template>

<script>
export default {
  props: {
    premium: {
      type: Boolean,
      required: true,
    },
  },
};
</script>

<style>
</style>template