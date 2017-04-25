<template>
  <div class="content">
    <main class="messages">
      <messages />
    </main>
    <footer>
      <add-message />
    </footer>
  </div>
</template>

<script>
  import Messages from './Messages.vue'
  import AddMessage from './AddMessage.vue'
  export default {
    components: { AddMessage, Messages }
  }
</script>

<style lang="scss" scoped></style>
