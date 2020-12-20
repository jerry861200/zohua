<template>
  <!-- <div class="bg-index"> -->
    <div class="container">
      <b-card-group deck>
        <b-card
          img-src="../assets/img/fish.svg"
          img-alt="子瑜的店"
          img-top
          
          title="燈泡魚"
          class="card-width"
          no-body
        >
          <b-card-body class="pb-1">
            <b-card-title class="red"> 燈泡魚 </b-card-title>
            <b-card-text> 輕食/甜點/西式主餐 </b-card-text>
          </b-card-body>

          <b-button variant="orange" to="./storeItems/1" squared class="h"
            >看菜單</b-button
          >
        </b-card>

        <b-card
          img-src="../assets/img/1997.jpg"
          img-alt="林聖翔的店"
          img-top
          title="1997手工窯烤披薩"
          
          class="card-width"
          no-body
        >
          <b-card-body class="pb-1">
            <b-card-title class="red"> 1997手工窯烤披薩 </b-card-title>
            <b-card-text> 窯烤披薩/美式炸物/甜點 </b-card-text>
          </b-card-body>
          <b-button variant="orange" to="./storeItems/2" squared class="h"
            >看菜單</b-button
          >
        </b-card>

        <b-card
          img-src="../assets/img/corridor_logo.png"
          img-alt="合作的店"
          img-top
          title="飲廊corridor"
          
          class="card-width"
          no-body
        >
          <b-card-body class="pb-1">
            <b-card-title class="red"> 飲廊corridor </b-card-title>
            <b-card-text> 義式燉麵飯/輕食甜點/調酒 </b-card-text>
          </b-card-body>
          <b-button variant="orange" to="./storeItems/1" squared class="h"
            >看菜單</b-button
          >
        </b-card>
      </b-card-group>

      <b-card-group deck class="mt-3">
        <b-card
          img-src="../assets/img/fang_rice_logo.jpg"
          img-alt="子瑜的店"
          img-top
          
          title="阿芳鹹粥"
          class="card-width"
          no-body
        >
          <b-card-body class="pb-1">
            <b-card-title class="red"> 阿芳鹹粥 </b-card-title>
            <b-card-text> 特色鹹粥／祖傳滷味 </b-card-text>
          </b-card-body>
          <b-button variant="orange" to="./storeItems/1" squared class="h"
            >看菜單</b-button
          >
        </b-card>

        <b-card
          img-src="https://scontent.ftpe8-1.fna.fbcdn.net/v/t1.0-9/26731050_1777929862268588_4747268120947166718_n.jpg?_nc_cat=108&ccb=2&_nc_sid=09cbfe&_nc_ohc=x4KiS6qRh1IAX9rbPKK&_nc_ht=scontent.ftpe8-1.fna&oh=6e8e70f7b347684016b2bff9b20748b3&oe=60039D7C"
          img-alt="微笑月亮手作甜點"
          img-top
          title="微笑月亮手作甜點"
          
          class="card-width"
          no-body
        >
          <b-card-body class="pb-1">
            <b-card-title class="red"> BF burger </b-card-title>
            <b-card-text> 美式漢堡／義式主食/炸物 </b-card-text>
          </b-card-body>
          <b-button variant="orange" to="./storeItems/1" squared class="h"
            >看菜單</b-button
          >
        </b-card>
        <b-card
          img-src="../assets/img/teacher_bbq.jpg"
          img-alt="合作的店"
          img-top
          title="哩老師烤好"
          
          class="card-width"
          no-body
        >
          <b-card-body class="pb-1">
            <b-card-title class="red"> 哩老師烤好 </b-card-title>
            <b-card-text> 行動BBQ </b-card-text>
          </b-card-body>
          <b-button variant="orange" to="./storeItems/6" squared class="h"
            >看菜單</b-button
          >
        </b-card>
      </b-card-group>
    </div>
  <!-- </div> -->
</template>

<script>
import Stars from "../components/Stars.vue";
import MainButton from "../components/utils/MainButton.vue";
export default {
  components: { MainButton, Stars },
  data() {
    return {
      solid: true,
    };
  },
};
</script>

<style scoped>
.card-width {
  max-width: 17rem;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding-top: 100px;
}
.btn-orange {
  background-color: #f3c19d;
  color: white;
  border-color: #f3c19d;
  transition: all 0.5s;
}
.btn-orange:hover {
  background-color: #f78454;
  color: white;
  border-color: #f78454;
}
.h {
  line-height: 35px;
  font-size: 25px;
}

.red {
  color: #b22323;
}

.bg-index {
  background-image: url("../assets/img/web_background.png");
  background-size: cover;
  background-position: center center;
  /* background-repeat: no-repeat; */
  height: 150vh;
}

@media (max-width: 740px) {
  .bg-index {
    background-image: url("../assets/img/bg_footer_app.jpg");
    background-size: cover;
    background-position: center center;
    background-repeat: no-repeat;
  }
}
</style>
