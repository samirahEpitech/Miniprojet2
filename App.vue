<template>
  <div id="app">
  <ul>
    <li>
      <p>{{ moment(date).format('MMMM Do YYYY, h:mm:ss a') }}</p>
      
    </li>
  </ul>
</div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
