<template>
  <div class="footer-background mt-4">
    <div class="container text-center">
      <b-row class="first-row pt-5 title">
        <b-col cols="12" md="6" class="title"> 聯絡資訊 </b-col>
        <b-col cols="12" md="6" class="title">客服專區</b-col>
      </b-row>
      <b-row class="mt-4">
        <b-col cols="12" md="6" class="content"> 電話：0929232210 </b-col>
        <b-col cols="12" md="6" class="content"
          ><a href="https://lin.ee/XwGVgkX"> Line:@731glya </a></b-col
        >
      </b-row>
      <b-row class="mt-3">
        <b-col cols="12" md="6" class="content">
          信箱:jimmy5811223@gmail.com
        </b-col>
        <b-col cols="12" md="6" class="content"></b-col>
      </b-row>
    </div>
  </div>
</template>

<style scoped>
.title {
  font-weight: 500;
  color: #3c3c3c;
  font-size: 28px;
}
.content {
  font-weight: 500;
  color: #3c3c3c;
}
a {
  text-decoration: none;
  color: #3c3c3c;
}
a:hover {
  color: #31373b;
}
* {
  font-weight: 400;
  font-size: 16px;
}
.footer-background {
  background-color: #f4b284;
  height: 250px;
  z-index: 2;
}
</style>
