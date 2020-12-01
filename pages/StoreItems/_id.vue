<template>
  <div class="container">
      <h3 class="introduction">嗨，我是世恩專員，讓我為你介紹最適合你的外匯餐點</h3>
      <Contact/>
      <h3 class="store-name">燈泡魚</h3>
    <b-card-group deck>
      <b-card
        img-src="https://scontent.frmq3-2.fna.fbcdn.net/v/t1.0-9/119044435_2766203873613961_6104754275591500574_o.jpg?_nc_cat=100&ccb=2&_nc_sid=8bfeb9&_nc_ohc=CDq7PhXnfLAAX_Wsm8m&_nc_ht=scontent.frmq3-2.fna&oh=977317903b27da686279e990cb182874&oe=5FEADA61"
        img-alt="菇雞菇雞鹹派"
        img-top
        img-height='250'
        title="菇雞菇雞鹹派"
        sub-title="$300-800"
      >
      </b-card>

      <b-card
        img-src="https://scontent.frmq3-1.fna.fbcdn.net/v/t1.0-9/118306915_2751903941710621_9067751118413411053_o.jpg?_nc_cat=105&ccb=2&_nc_sid=a26aad&_nc_ohc=auaoUmHULjUAX9DnTGH&_nc_ht=scontent.frmq3-1.fna&oh=ce51aafdd1c526226abd2ec5d2bb2c70&oe=5FEA73FC"
        img-alt="蜂蜜甜橙瑪德蓮"
        img-top
        title="蜂蜜甜橙瑪德蓮"
        img-height='250'
        sub-title="$100-600"
      >
      </b-card>
      <b-card
        img-src="https://scontent.frmq3-2.fna.fbcdn.net/v/t1.0-9/117147906_2730425003858515_2455799660133954138_o.jpg?_nc_cat=100&ccb=2&_nc_sid=a26aad&_nc_ohc=eew7Bt7QaXIAX_Pgy8k&_nc_ht=scontent.frmq3-2.fna&oh=50709e66c87b500af28e5921f89f4810&oe=5FEB197D"
        img-alt="經典檸檬塔"
        img-top
        title="經典檸檬塔"
        img-height='250'
        sub-title="不要訂這個"
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
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding-top:100px;
}
.place-question {
  color: #6558f6;
  padding-bottom: 40px;
  margin-top: -100px;
}
.btn-left {
  margin-right: 30px;
}
.introduction{
    margin-bottom: 20px;
}
.contact{
    margin-bottom: 20px;
}
b-card{
    max-height: 15px;
}
.store-name{
    align-self: start;
}
</style>
