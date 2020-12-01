<template>
  <div class="container">
    <div class="left-div">
      <h3 class="place-question">聚會的舉辦日期是?</h3>
      <b-form-datepicker
        id="example-datepicker"
        v-model="date"
        class="mb-2 p-2"
        placeholder="選擇日期"
      ></b-form-datepicker>
    </div>
    <div class="right-div">
      <b-form-input
        id="place"
        v-model.trim="place"
        type="text"
        required
        placeholder="輸入活動地址"
        width="400"
        class="p-4"
      ></b-form-input>
      <b-button variant="purple" href="./store" class="search" size="lg"
        >找尋適合的外燴</b-button
      >
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      date: "",
      place: "",
    };
  },
};
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-top: -200px;
}
.place-question {
  color: #6558f6;
  padding-bottom: 20px;
}
.left-div {
  margin-right: 150px;
}
.right-div {
  min-width: 300px;
}
.search {
  margin-top: 20px;
  margin-right: 165px;
}
/* ::placeholder { 
  color: #302e2e;
} */
.btn-purple{
    background-color: #6558f6;
    color: white;
}
</style>