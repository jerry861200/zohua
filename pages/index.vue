<template>
  <div class="container">
    <h3 class="place-question">活動將在哪舉行呢?</h3>
    <div>
      <b-button variant="outline-dark" href="./dateForm" size="lg" class="btn-left">台北</b-button>
      <b-button variant="outline-dark" href="./dateForm" size="lg">宜蘭</b-button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-top: -200px;
}
.place-question{
  color: #6558f6;
  padding-bottom: 40px;
  
}
.btn-left{
  margin-right: 30px;
}
</style>
