<template>
  <div id="app">
    <div class="side">
      <list-chat />
      <add-contact />
    </div>
    <div class="full">
      <chat-content />
    </div>
  </div>
</template>

<script>
  import ListChat from './ListChat.vue'
  import ChatContent from './ChatContent.vue'
  import AddContact from './AddContact.vue'
  export default {
    components: { ListChat, ChatContent, AddContact }
  }
</script>

<style lang="sass" src="../styles/style.sass"></style>
