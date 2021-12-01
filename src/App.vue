<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'Vai da onda?',
  meta: [
    { name: 'description', content: 'Uma simples visualização das ondas no espírito santo' },
  ],
})
</script>

<template>
  <router-view />
</template>
