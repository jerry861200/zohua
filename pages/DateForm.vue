<template>
  <b-row class="row-height ">
    <b-col cols="12" md="6" class="shan-sian-img "> </b-col>
    <b-col cols="12" md="6">
      <div class="container pt-5">
        <img src="../assets/img/avatar.png" alt="" class="avatar">
        <h3 class="place-question ">哇，是宜蘭！</h3>
        <h3 class="place-question ">就讓宜蘭最懂活動餐點的平台為您介紹</h3>
        <b-form-datepicker
          id="example-datepicker"
          v-model="date"
          class="mb-4 p-2 mt-4 w-480" 
          placeholder="選擇日期"
          width="400"
        ></b-form-datepicker
        ><b-form-input
          id="place"
          v-model.trim="place"
          type="text"
          placeholder="輸入活動地址"
          width="400"
          class="p-4 w-480"
        ></b-form-input>
        <b-button variant="orange" class="search" size="lg" to="./store"
          >找尋適合的外燴</b-button
        >
      </div>
    </b-col>
  </b-row>
</template>

<script>
export default {
  data() {
    return {
      date: "",
      place: "",
    };
  },
  computed: {
    submitOK() {
      return this.date && this.place && true;
    },
  },
};
</script>

<style scoped>
.container {
  /* min-height: 100vh; */
}
.avatar{
  width: 300px;
  height: auto;
}
.row-height {
  height: 88vh;
}
.place-question {
  color: #f78454;
  
}
.search {
  margin-top: 20px;
  margin-right: 165px;
}
.btn-orange {
  background-color: #f78454;
  color: white;
}
.shan-sian-img {
  background-position: center;
  background-size: cover;
  /* background-attachment: fixed; */
  overflow-x: hidden;
  background-image: url(../assets/img/1997_shawn_3.png);
  background-position-x: right;
}
.w-480{
  width: 480px;
}
</style>