<template>
  <li class="contact">
    <a href="#" class="contact-link">
      <img :src="info.avatar" alt="info.username" class="contact-avatar">
      <h3 class="contact-name">{{ info.username }}</h3>
    </a>
  </li>
</template>

<script>
  export default {
    props: ['info']
  }
</script>

<style lang="scss" scoped>

</style>
