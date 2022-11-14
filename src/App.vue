<script setup>
  import {ref} from "vue"

  const count = ref(0)
</script>

<template>
  <main>
    <div>
      <h4>the current count is...</h4>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main>
</template>

<style scoped>
  main{
    background-color: aqua;
    height: 100vh;
    width:100vw;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  div{
    text-align: center;
  }
  button{
    width: 30px;
    height: 30px;
    margin: 10px;
    font-size: larger;
    color: red;
  }
</style>
