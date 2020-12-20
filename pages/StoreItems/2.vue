<template>
  <div class="container">
    <div class="topic-img mt-4 mb-4"></div>
    <div class="blabla">
      <b-row>
        <b-col md="3"></b-col>
        <b-col md="6">
          <h5>挑到喜歡的菜單了嗎!</h5>
          <h5>聯絡作燴替你準備</h5>
          <Contact />
          <h4 class="mt-4 black">菜單介紹</h4>
        </b-col>
        <b-col md="3">
          <img src="../../assets/img/1997.jpg" alt="" class="store-logo" />
          <h5 class="main-food">1997手工窯烤披薩</h5>
        </b-col>
      </b-row>
    </div>

    <b-card-group columns class="mb-3">
      <b-card no-body>
        <b-card-body class="text-center">
          <h4 class="main-food">-主餐-</h4>
          <p class="content">
            熱情夏威夷披薩 <br />
            經典瑪格麗特披薩 <br />
            義式傳統臘腸披薩 <br />
            招牌蜂蜜起司披薩 <br />
          </p>
          <h4 class="snack">-點心-</h4>
          <p class="content">美式脆薯 <br /></p>
          <h4 class="drink">-湯品&飲品-</h4>
          <p class="content">松柏嶺青茶 <br /></p>
        </b-card-body>
        <b-list-group flush>
          <b-list-group-item class="blabla price">350/人</b-list-group-item>
          <b-list-group-item class="content"
            >平日最低訂購:18人</b-list-group-item
          >
          <b-list-group-item class="content"
            >假日最低訂購:35人</b-list-group-item
          >
        </b-list-group>
      </b-card>
      <b-card no-body>
        <b-card-body class="text-center">
          <h4 class="main-food">-主餐-</h4>
          <p class="content">
            宜蘭蔥鴨胸披薩<br />
            瑪格麗特皇后披薩 <br />
            青醬野菇雞肉披薩 <br />
            核桃蜂蜜起司披薩 <br />
          </p>
          <h4 class="snack">-點心-</h4>
          <p class="content">切達起司薯條  <br />
          爐烤義式蔬菜</p>
          <h4 class="drink">-湯品&飲品-</h4>
          <p class="content">馬鈴薯奶油蘑菇濃湯 <br />
          義豐冬瓜青茶</p>
        </b-card-body>
        <b-list-group flush>
          <b-list-group-item class="blabla price">500/人</b-list-group-item>
          <b-list-group-item class="content"
            >平日最低訂購:12人</b-list-group-item
          >
          <b-list-group-item class="content"
            >假日最低訂購:24人</b-list-group-item
          >
        </b-list-group>
      </b-card>
      <!-- 第三個 -->
      <b-card no-body>
        <b-card-body class="text-center">
          <h4 class="main-food">-主餐-</h4>
          <p class="content">
            宜蘭蔥鴨胸披薩  <br />
            瑪格麗特皇后披薩  <br />
            白醬松露野菇披薩 <br />
            青醬漁夫海鮮披薩 <br />
            核桃蜂蜜起司披薩 <br/>
            榛果巧克力布朗尼披薩 <br/>
            爐烤大溪漁港透抽 <br/>
烤prime美國厚切牛小排 
          </p>
          <h4 class="snack">-點心-</h4>
          <p class="content">松露薯條 <br />
          切達起司炸雞</p>
          <h4 class="drink">-湯品&飲品-</h4>
          <p class="content">紅茶拿鐵 <br />
          番茄海鮮湯</p>
        </b-card-body>
        <b-list-group flush>
          <b-list-group-item class="blabla price">800/人</b-list-group-item>
          <b-list-group-item class="content"
            >平日最低訂購:12人</b-list-group-item
          >
          <b-list-group-item class="content"
            >假日最低訂購:20人</b-list-group-item
          >
        </b-list-group>
      </b-card>
      
    </b-card-group>
  </div>
</template>

<script>
import Contact from "../../components/Contact.vue";
export default {
  components: { Contact },
};
</script>

<style scoped>
.price {
  font-size: 24px;
  font-weight: 450;
}
.black {
  color: #293845;
}
.container {
  min-height: 100vh;
}
.store-logo {
  width: 150px;
  object-fit: contain;
}
.blabla {
  text-align: center;
  color: #f78454;
}
.border-p {
  border: #e1e7ec 2px solid;
}
.boss-name {
  color: #293845;
  font-weight: 800;
}

.topic-img {
  background-image: url("../../assets/img/mozarella.png");
  background-size: cover;
  height: 25rem;
}
.paragraph {
  font-weight: 700;
  color: #4c5964;
  font-size: 20px;
}
.content {
  font-weight: 450;
  font-size: 20px;
}
.main-food {
  color: #bf4a49;
}
.snack {
  color: #f78454;
}
.drink {
  color: #539eb8;
}
</style>
