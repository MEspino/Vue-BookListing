<template>
  <div>
      <ul>
        <book-item v-for="book in books" :book='book'></book-item>
      </ul>

  </div>
</template>

<script>
  export default {
    name: 'BookItem',
    components: {
      BookItem
    },
    props: [
      'book'
    ]

  }
</script>

<style lang="css" scoped>
li {
  display: block;
  margin: 0 10px
}
</style>
