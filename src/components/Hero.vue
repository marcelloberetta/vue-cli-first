<template>
  <div>
    <img src="../assets/guida-vue-js-italiano.png" alt="">
    <h2>Vue è un altro mondo!</h2>
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped>

div{
  width: 1200px;
  margin: 0 auto;
  border-radius: 25px;
  background-color:gray;
  text-align: center;
  overflow: hidden;
  position: relative;
}
img{
  width: 100%;
  vertical-align: bottom;
}
h2{
  font-size: 40px;
  color: #4D6A8C;
  text-shadow: 1px 1px #000;
  position: absolute;
  top: 50px;
  left: 50%;
  transform: translateX(-50%);
}

</style>