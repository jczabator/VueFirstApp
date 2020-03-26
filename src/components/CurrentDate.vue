<template>
  <span v-bind:title="message + new Date().toLocaleString()">
    Hover your mouse over me for a few seconds
    to see my dynamically bound title!
  </span>
</template>

<script>
export default {
  name: 'CurrentDate',
  props: {
    message: String
  }
}
</script>