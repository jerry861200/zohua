<template>
  <b-row class="row-height ">
    <b-col cols="12" md="5" class="shan-sian-img "> </b-col>
    <b-col cols="12" md="7">
      <div class="container pt-5">
        <h3 class="place-question ">讓宜蘭最懂外燴的平台為你介紹</h3>
        <b-form-datepicker
          id="example-datepicker"
          v-model="date"
          class="mb-2 p-2"
          placeholder="選擇日期"
        ></b-form-datepicker
        ><b-form-input
          id="place"
          v-model.trim="place"
          type="text"
          placeholder="輸入活動地址"
          width="400"
          class="p-4"
        ></b-form-input>
        <b-button variant="purple" class="search" size="lg" to="./store"
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
.row-height {
  height: 70vh;
}
.place-question {
  color: #6558f6;
  padding-bottom: 20px;
}
.search {
  margin-top: 20px;
  margin-right: 165px;
}
.btn-purple {
  background-color: #6558f6;
  color: white;
}
.shan-sian-img {
  background-position: center;
  background-size: cover;
  /* background-attachment: fixed; */
  overflow-x: hidden;
  background-image: url(https://scontent.ftpe12-1.fna.fbcdn.net/v/t31.0-8/26233526_1718355021558900_3161593798765919149_o.jpg?_nc_cat=106&ccb=2&_nc_sid=730e14&_nc_ohc=ILkQaE8nQzcAX_qQPmh&_nc_ht=scontent.ftpe12-1.fna&oh=2d4968f25116b60f2621b6bd13e157c9&oe=5FEE4E3F);
}
</style>