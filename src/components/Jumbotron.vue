<template>
  <div>
    <div class="quadrati">
      <div class="quadrato"></div>
      <div class="quadrato"></div>
      <div class="quadrato"></div>
      <img src="../assets/logo.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name:'Jumbotron'
}
</script>

<style scoped>
  .quadrati{
    display: flex;
    height: 400px;
    width: 100%;
    justify-content: space-around;
    align-items: center;
    margin: auto;
  }
  .quadrato{
    height: 100px;
    width: 100px;
    background-color: red;
  }
</style>