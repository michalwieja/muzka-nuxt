<template>
  <NuxtLink :to="link" :class="['link', variant]">
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
    link: {
      type: String
    },
    variant: {
      type: String
    }
  }
}
</script>
