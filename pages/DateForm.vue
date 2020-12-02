<template>
  <div class="container">
    <b-row align-v="center" class="row-height">
      <b-col cols="12" md="6"
        ><h3 class="place-question">聚會的舉辦日期是?</h3>
        <b-form-datepicker
          id="example-datepicker"
          v-model="date"
          class="mb-2 p-2"
          placeholder="選擇日期"
        ></b-form-datepicker
      ></b-col>
      <b-col cols="12" md="6"
        ><b-form-input
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
        ></b-col
      >
    </b-row>
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
  /* margin: 0 auto; */
  min-height: 100vh;
  /* display: flex; */
  /* justify-content: center; */
  /* align-items: center; */
  /* text-align: center; */
  /* margin-top: -200px; */
}
.row-height{
    height: 60vh;
}
.place-question {
  color: #6558f6;
  padding-bottom: 20px;
}
.search {
  margin-top: 20px;
  margin-right: 165px;
}
/* ::placeholder { 
  color: #302e2e;
} */
.btn-purple {
  background-color: #6558f6;
  color: white;
}
</style>