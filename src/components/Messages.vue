<template>
  <ul class="messages-list">
    <message :isUser="true"/>
    <message :isUser="false"/>
  </ul>
</template>

<script>
  import Message from './Message.vue'
  export default {
    components: { Message }
  }
</script>

<style lang="scss" scoped>

</style>
