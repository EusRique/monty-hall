<template>
  <div id="app">
    <h1>Problema de Monty Hall</h1>
    <Gift />
  </div>
</template>

<script>
import Gift from './components/Gift'

export default {
  name: 'App',
  components: { Gift }
}
</script>

<style>
  * {
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
  }

  #app {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #app h1 {
    border: 1px solid #DF8226;
    background-color: #fba617;
    color: #fff;
    padding: 20px;
    margin-bottom: 60px;
  }
</style>