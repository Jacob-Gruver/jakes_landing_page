<template>
  <div class="about flex-grow-1 d-flex flex-column align-items-center justify-content-center">
    <!-- <h1>This is the about page</h1> -->
    <img class="" src="../assets/img/Gruver-Jacob.png">
  </div>
</template>

<script>
export default {
  name: 'AboutPage'
}
</script>
<style scoped lang="scss">
.about{
  animation:  fadeInAnimation ease 3s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
  @keyframes fadeInAnimation {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
}
}
img{
  height: 1800px;
  width: 1400px;
}

</style>
