<template>
  <div id="app">
    <h1>Problema de Monty Hall</h1>
    <mhDoor :number="1" :hasGift="false" />
  </div>
</template>

<script>
import mhDoor from './components/mhDoor.vue'

export default {
  name: 'App',
  components: { mhDoor }
}
</script>

<style>
* {
  box-sizing: border-box;
  font-family: 'Monserrat', sans-serif;
}

body {
  color: #fff;
  background: linear-gradient(to right, rgb(21, 153, 87), rgb(21, 87, 153));
}

#app {
  display: flex;
  flex-direction: column;
  align-items: center;
}

#app h1 {
  border: 1px solid #000;
  background-color: #0004;
  padding: 20px;
  margin-bottom: 60px;
}
</style>
