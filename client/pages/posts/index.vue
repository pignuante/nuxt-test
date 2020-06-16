<template lang="pug">
  v-container
    h1.page-title Posts
    p 블로그 포스트 목록
    .post-list
</template>

<script>
  export default {
    name: "index"
  }
</script>

<style scoped>
  .post-list {
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
