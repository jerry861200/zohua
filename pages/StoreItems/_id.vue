<template>
  <div class="container">
    <h2 class="store-name mt-4">1997手工窯烤披薩</h2>
    <div class="border-p p-5 mt-4 mb-5">
      <b-row>
        <b-col cols="6">
          <h3 class="mb-3 px-3 boss-name">林聖翔</h3>
      <p class="paragraph p-3">
        林聖翔從高中畢業起就在窯烤披薩店打工，上了宜蘭大學後便創業做起窯烤披薩餐車，累積了7年的功夫，認真烤好每一片經典拿坡里式披薩，每片披薩都經過24小時的天然發酵，以及600度高溫的義式窯烤，最後撒上純天然的進口起司，絕對是作燴平台認可宜蘭第一的披薩
      </p>
        </b-col>
        <b-col cols="6">
          <div class="boss-img2"></div>
        </b-col>
      </b-row>
      
    </div>
    <b-card-group deck class="mb-3">
      <b-card
        img-src="../../assets/img/美式臘腸.png"
        img-alt="菇雞菇雞鹹派"
        img-top
        img-height="250"
        title="義式傳統臘腸"
        class="menu-card pt-2 px-2"
      >
      </b-card>

      <b-card
        img-src="../../assets/img/莫札瑞拉.png"
        img-alt="蜂蜜甜橙瑪德蓮"
        img-top
        title="經典瑪格麗特"
        img-height="250"
        
        class="menu-card pt-2 px-2"
      >
      </b-card>
      <b-card
        img-src="../../assets/img/海鮮.png"
        img-alt="經典檸檬塔"
        img-top
        title="宜蘭漁夫海鮮"
        img-height="250"
        
        class="menu-card pt-2 px-2"
      >
      </b-card>
    </b-card-group>
    <b-card-group deck>
      <b-card
        img-src="../../assets/img/mushroom.png"
        img-alt="菇雞菇雞鹹派"
        img-top
        img-height="250"
        title="新鮮松露野菇"
        
        class="menu-card pt-2 px-2"
      >
      </b-card>

      <b-card
        img-src="../../assets/img/夏威夷.png"
        img-alt="蜂蜜甜橙瑪德蓮"
        img-top
        title="熱情夏威夷"
        img-height="250"
        class="menu-card pt-2 px-2"
      >
      </b-card>
      <b-card
        img-src="../../assets/img/fried.jpg"
        img-alt="經典檸檬塔"
        img-top
        title="時光炸物拼盤"
        img-height="250"
        class="menu-card pt-2 px-2"
      >
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  min-height: 100vh;
}
.place-question {
  color: #6558f6;
  padding-bottom: 40px;
  margin-top: -100px;
}
.btn-left {
  margin-right: 30px;
}
.store-name {
  color: #f78454;
  font-weight: 900;
}
.border-p {
  border: #e1e7ec 2px solid;
}
.boss-name{
  color: #293845;
  font-weight: 800;
}
.boss-img{
  width: 250px;
}
.boss-img2{
  background-image: url("../../assets/img/1997_shawn.jpg");
  background-size: cover;
  height: 18rem;
}
.paragraph{
  font-weight: 700;
  color: #4c5964;
  font-size: 20px;
}
.menu-card{
  border: #f78454 2px solid;
  text-align: center;
  color: #f78454;
}
.card-title{
  font-weight: 900;
}
</style>
