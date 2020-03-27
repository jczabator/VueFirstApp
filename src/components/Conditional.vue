<template>
  <span v-if="seen">Now u see me</span>
</template>

<script>
export default {
  name: 'Conditional',
  props: {
    seen: Boolean
  }  
}
</script>