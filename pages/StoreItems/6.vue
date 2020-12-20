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
          <h5 class="main-food">哩老師烤好</h5>
        </b-col>
      </b-row>
    </div>

    <b-card-group columns class="mb-3">
      <b-card no-body>
        <b-card-body class="text-center">
          <h4 class="main-food">-肉類-</h4>
          <p class="content">
            炭燒豬肋排<br />
            日式鹹豬肉 <br />
            宜蘭玉田香腸 <br />
            鹽烤櫻桃鴨腿肉串 <br />
            美國pm無骨牛小排<br />
            碳烤溫體黑毛梅花豬
          </p>
          <h4 class="drink">-海鮮-</h4>
          <p class="content">
            炭烤椒鹽鳳螺<br />
            炭烤金車無毒大白蝦 <br />
            碳烤招牌魚下巴 <br />
            鹽烤干貝天婦羅
          </p>
          <h4 class="vegetable">-時蔬-</h4>
          <p class="content">炭烤時令蔬菜</p>
        </b-card-body>
        <b-list-group flush>
          <b-list-group-item class="blabla price">1000/人</b-list-group-item>
          <b-list-group-item class="content"
            >平日最低訂購:12人</b-list-group-item
          >
          <b-list-group-item class="content"
            >假日最低訂購:15人</b-list-group-item
          >
          <b-list-group-item class="content"
            >連續假日最低訂購 : 20人</b-list-group-item
          >
        </b-list-group>
      </b-card>
      <!-- 第二個 -->
      <b-card no-body>
        <b-card-body class="text-center">
          <h4 class="main-food">-肉類-</h4>
          <p class="content">
            炭燒豬肋排<br />
            宜蘭玉田香腸 <br />
            碳烤溫體松阪豬 <br />
            美國pm無骨牛小排<br />
            碳烤溫體梅花豬卷5寶
          </p>
          <h4 class="drink">-海鮮-</h4>
          <p class="content">
            炭烤椒鹽鳳螺<br />
            碳烤招牌魚下巴 <br />
            碳烤活鮑魚嫩切
            <br />
            碳烤北海道生食級干貝<br />
            炭烤頂級海藻養殖白蝦
          </p>
          <h4 class="vegetable">-時蔬-</h4>
          <p class="content">炭烤時令蔬菜</p>
        </b-card-body>
        <b-list-group flush>
          <b-list-group-item class="blabla price">1500/人</b-list-group-item>
          <b-list-group-item class="content"
            >平日最低訂購:8人</b-list-group-item
          >
          <b-list-group-item class="content"
            >假日最低訂購:10人</b-list-group-item
          >
          <b-list-group-item class="content"
            >連續假日最低訂購 : 14人</b-list-group-item
          >
        </b-list-group>
      </b-card>
      <!-- 第三個 -->
      <b-card no-body>
        <b-card-body class="text-center">
          <h4 class="main-food">-肉類-</h4>
          <p class="content">
            炭燒豬肋排<br />
            宜蘭玉田香腸 <br />
            碳烤溫體松阪豬 <br />
            美國pm無骨牛小排<br />
            鹽烤澳洲M9和牛牛舌<br />
            碳烤溫體梅花豬卷5寶
          </p>
          <h4 class="drink">-海鮮-</h4>
          <p class="content">
            碳烤活龍蝦<br />
            碳烤時令鮮魚<br />
            碳烤活鮑魚嫩切
          </p>
          <h4 class="vegetable">-時蔬-</h4>
          <p class="content">炭烤時令蔬菜</p>
        </b-card-body>
        <b-list-group flush>
          <b-list-group-item class="blabla price">2000/人</b-list-group-item>
          <b-list-group-item class="content"
            >平日最低訂購:6人</b-list-group-item
          >
          <b-list-group-item class="content"
            >假日最低訂購:8人</b-list-group-item
          >
          <b-list-group-item class="content"
            >連續假日最低訂購 : 10人</b-list-group-item
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
.vegetable {
  color: #73b83a;
}
</style>
