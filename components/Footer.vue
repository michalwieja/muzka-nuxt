<template>
  <footer class="footer wrapper playfair">
    Copyright &copy; MW {{ currentDate.getFullYear() }}
    All rights reserved
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {
      currentDate: new Date()
    }
  }
}
</script>
