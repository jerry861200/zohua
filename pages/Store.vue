<template>
  <div class="container">
    <h3 class="introduction">
      嗨，我是世恩專員，讓我為你介紹最適合你的外匯餐點
    </h3>
    <Contact />
    <b-card-group deck>
      <b-card
        img-src="https://scontent.frmq3-2.fna.fbcdn.net/v/t1.0-9/125427081_2836015216632826_5778174829632141269_o.jpg?_nc_cat=107&ccb=2&_nc_sid=8bfeb9&_nc_ohc=SPiCFxN07o0AX8el7Ct&_nc_ht=scontent.frmq3-2.fna&oh=8c50db78803b2c323adbe8430436f2d7&oe=5FEB90E4"
        img-alt="子瑜的店"
        img-top
        img-height="225"
        title="燈泡魚"
        sub-title="$300-800"
      >
        <b-card-text>
          Some quick example text to build on the card and make up the bulk of
          the card's content.
        </b-card-text>
        <b-button href="./storeItems/1" variant="outline-purple">選擇</b-button>
      </b-card>

      <b-card
        img-src="https://scontent.ftpe12-1.fna.fbcdn.net/v/t31.0-8/26233526_1718355021558900_3161593798765919149_o.jpg?_nc_cat=106&ccb=2&_nc_sid=730e14&_nc_ohc=gjZRUKUbc3QAX_Z-1JD&_nc_ht=scontent.ftpe12-1.fna&oh=8a196f472026152848ff6107b6e951ab&oe=5FEA59BF"
        img-alt="林聖翔的店"
        img-top
        title="1997手工窯烤披薩"
        img-height="225"
        sub-title="$100-600"
      >
        <b-card-text>
          Some quick example text to build on the card and make up the bulk of
          the card's content.
        </b-card-text>
        <b-button href="./storeItems/2" variant="outline-purple">選擇</b-button>
      </b-card>
      <b-card
        img-src="http://www.mrogenki.com/images/imgSec1-1_index.jpg"
        img-alt="合作的店"
        img-top
        title="元氣先生"
        img-height="225"
        sub-title="不要訂這個"
      >
        <b-card-text>
          Some quick example text to build on the card and make up the bulk of
          the card's content.
        </b-card-text>
        <b-button href="./storeItems/3" variant="outline-purple">選擇</b-button>
      </b-card>
    </b-card-group>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding-top: 100px;
}
.place-question {
  color: #6558f6;
  padding-bottom: 40px;
  margin-top: -100px;
}
.btn-left {
  margin-right: 30px;
}
.introduction {
  margin-bottom: 20px;
}
</style>
