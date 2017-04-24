<template>
  <ul class="list-contacts">
    <contact v-for="contact in contacts" :key="contact.id" :info="contact" />
  </ul>
</template>

<script>
  import Contact from './Contact.vue'
  export default {
    components: { Contact },
    data () {
      return {
        contacts: [
          { id: 1, username: 'erikprogramador', email: 'erikprogramador@erikprogramador.com', avatar: 'https://unsplash.it/100/100' },
          { id: 2, username: 'erikmbx', email: 'programador@programador.com', avatar: 'https://unsplash.it/100/100' },
          { id: 3, username: 'programmer', email: 'programmer@programmer.com', avatar: 'https://unsplash.it/100/100' }
        ]
      }
    }
  }
</script>

<style lang="scss" scoped></style>
