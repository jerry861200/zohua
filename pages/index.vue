<template>
  <div>
    <div class="container">
      <img src="../assets/img/avatar.png" alt="" class="avatar ml-4">
      <h4 class="fw-400">Hi!我是Smile，我會問您介紹最適合您活動的餐點</h4>
      <h4 class="place-question m-3">告訴我活動將在哪裡舉行吧！</h4>
        <div>  
          <b-button
            variant="outline-dark"
            href="./dateForm"
            size="lg"
            class="btn-left"
            disabled
            >台北</b-button
          >
          <b-button variant="outline-dark" href="./dateForm" size="lg"
          >宜蘭</b-button
        >
        </div>
        <small class="small">即將開放!</small>
        
      </div>
    <Footer />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.fw-400{
  font-weight: 400;
}
.avatar{
  width: 300px;
  height: auto;
}
.container {
  min-height: 56vh;
  text-align: center;
}
.small{
  margin-right: 112px;
}
.place-question {
  color: #f78454;
  padding-bottom: 10px;
}
.btn-left {
  margin-right: 30px;
}

</style>
