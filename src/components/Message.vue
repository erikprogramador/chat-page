<template>
  <li class="message" :class="{ 'bubble-user': isUser }">
    <div class="message-bubble">
      <h5 class="bubble-title">Buble Username</h5>
      <p class="bubble-description">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae tempore ipsa ad, hic dolor, neque sed dolorum, dolores aliquid, repudiandae tempora aperiam voluptatibus. Autem dicta hic, odit amet harum nihil?</p>
    </div>
  </li>
</template>

<script>
  export default {
    props: ['isUser']
  }
</script>

<style lang="scss" scoped>

</style>
