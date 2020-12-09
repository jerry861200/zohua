<template>
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
</template>

<style>
.logo {
  width: 150px;
  height: auto;
}
.navbar-border {
  /* border-width: medium; */
  border: #cdcdcd 1.4px solid;
}
.btn-orange {
  background-color: #f78454;
  color: white;
  border-color: #f78454;
}
</style>
