<template>
  <div id="app">
    <div class="side">
      <list-chat />
    </div>
    <div class="full">
      <chat-content />
    </div>
  </div>
</template>

<script>
  import ListChat from './ListChat.vue'
  import ChatContent from './ChatContent.vue'
  export default {
    components: { ListChat, ChatContent }
  }
</script>

<style lang="sass" src="../styles/style.sass"></style>
