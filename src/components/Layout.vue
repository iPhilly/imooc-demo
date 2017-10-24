<template>
  <div>
    <div class="app-header">header</div>
    <div class="app-content">content</div>
    <div class="app-footer">footer</div>
    <h1>{{msg}}</h1>
    <button @click="addOne">add one</button>
    <button @click="minusOne">minus one</button>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        msg: 'i am apple',
        price: 5
      }
    },
    methods: {
      addOne() {

      },
      minusOne() {

      }
    }

  }
</script>
