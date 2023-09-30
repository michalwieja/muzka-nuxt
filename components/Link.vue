<template>
  <NuxtLink to="/onas" class="link">
    {{ `${label} >` }}
  </NuxtLink>
</template>

<script>
export default {
  name: 'Link',
  props: {
    label: {
      type: String
    },
  }
}
</script>
