<template>
  <button class="button" @click="handleClick">
    {{ label }}
  </button>
</template>

<script>
export default {
  name: 'Button',
  props: {
    label: {
      type: String
    },
    handleClick: {
      type: Function,
      default: () => { }
    }
  }
}
</script>
