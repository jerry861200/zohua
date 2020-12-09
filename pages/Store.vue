<template>
  <div class="container">
    <Contact />
    <b-card-group deck>
      <b-card
        img-src="../assets/img/bulb_fish_logo.jpg"
        img-alt="子瑜的店"
        img-top
        img-height="225"
        title="燈泡魚"
        class="card-width"
        no-body
      >
        <b-card-body>
          <b-card-title>
            燈泡魚
          </b-card-title>
          <b-card-text> 輕食/甜點/西式主餐 </b-card-text>
          <Stars />
        </b-card-body>
        <!-- <MainButton location="./storeItems/1" :solid="solid" 
          >選擇</MainButton
        > -->
        <b-button variant="orange" to="./storeItems/1" squared>看看我的手路菜吧</b-button>
      </b-card>

      <b-card
        img-src="../assets/img/1997.jpg"
        img-alt="林聖翔的店"
        img-top
        title="1997手工窯烤披薩"
        img-height="225"
        class="card-width"
      >
        <b-card-text> 窯烤披薩/美式炸物/甜點 </b-card-text>
        <Stars />
        <MainButton location="./storeItems/2">選擇</MainButton>
      </b-card>
      <b-card
        img-src="../assets/img/corridor_logo.png"
        img-alt="合作的店"
        img-top
        title="飲廊corridor"
        img-height="225"
        class="card-width"
      >
        <b-card-text> 義式燉麵飯/輕食甜點/調酒 </b-card-text>
        <Stars />
        <MainButton location="./storeItems/3">選擇</MainButton>
      </b-card>
    </b-card-group>
    <b-card-group deck class="mt-3">
      <b-card
        img-src="../assets/img/fang_rice_logo.jpg"
        img-alt="子瑜的店"
        img-top
        img-height="225"
        title="阿芳鹹粥"
        class="card-width"
      >
        <b-card-text> 特色鹹粥／祖傳滷味 </b-card-text>

        <Stars />
        <MainButton location="./storeItems/4">選擇</MainButton>
      </b-card>

      <b-card
        img-src="../assets/img/smile_moon.jpg"
        img-alt="微笑月亮手作甜點"
        img-top
        title="微笑月亮手作甜點"
        img-height="225"
        class="card-width"
      >
        <b-card-text> 客製蛋糕／泡芙/西式點心 </b-card-text>
        <Stars />
        <MainButton location="./storeItems/5">選擇</MainButton>
      </b-card>
      <b-card
        img-src="../assets/img/teacher_bbq.jpg"
        img-alt="合作的店"
        img-top
        title="哩老師烤好"
        img-height="225"
        class="card-width"
      >
        <b-card-text> 行動BBQ </b-card-text>
        <Stars />
        <MainButton location="./storeItems/6">選擇</MainButton>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
import Stars from "../components/Stars.vue";
import MainButton from "../components/utils/MainButton.vue";
export default {
  components: { MainButton, Stars },
  data(){
    return {
      solid:true,
    }
  }
};
</script>

<style scoped>
.card-width {
  max-width: 18rem;
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
.btn-left {
  margin-right: 30px;
}
.btn-orange {
   background-color: #f3c19d;
  color: white;
  border-color: #f3c19d;
  transition: all 0.5s;
}
.btn-orange：hover {
   background-color: #f78454;
  color: white;
  border-color: #f78454;
}
</style>
