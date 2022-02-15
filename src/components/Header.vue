<template>
  <div id="header">
    <h1 class="container"><strong>Todo List</strong></h1>
    <div class="container">為你的金魚腦增加容量吧！</div>
  </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
 #header {
     display: flex;
     background-color: black;
     color: white;
     justify-content: center;
     align-items: center;
 }

 .container {
     margin: 10px;
 }
</style>