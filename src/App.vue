<script setup>
const message = 'Vue 3'
const name='Jonathan'
const year=2025
</script>

<template>
  <h1>Hello, {{message}}!</h1>

  <footer>
    <p>&copy; {{name}} {{ year }}</p>
  </footer>
  
</template>

<style scoped>
h1{
  font-weight: bold;
  text-align: center;
  margin-top: 50px;
}
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  text-align: center;
  font-family: serif;
}
</style>
