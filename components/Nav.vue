<template>
  <b-navbar variant="faded" type="light" class="stickey-top navbar-border">
    <div class="container">
      <NuxtLink to="/">
        <img class="logo" src="../assets/img/logo-1.png" alt="Kitten" />
      </NuxtLink>

      <div class="right">
        <h4 class="contact-title">讓作燴專員幫你推薦最適合的餐點</h4>
        <Contact />
      </div>
      <div class="avatar-container">
        <img src="../assets/img/smile_circle.jpg" alt="" class="avatar" />
      </div>
    </div>
  </b-navbar>
</template>

<style scoped>
.logo {
  width: auto;
  height: 130px;
}

.contact-title {
  color: #6d6d6d;
  margin-top: 15px;
  margin-left: 5px;
}
.navbar-border {
  /* border-width: medium; */
  border-bottom: #cdcdcd 3px solid;
}
.btn-orange {
  background-color: #f78454;
  color: white;
  border-color: #f78454;
}
.avatar-container {
  overflow-x: hidden;
}
.avatar {
  width: auto;
  height: 100px;
}
.right {
  margin-left: auto;
  margin-right: 14px;
}
@media (max-width: 740px) {
  .logo {
    width: auto;
    height: 60px;
  }
  .contact-title {
    color: #6d6d6d;
    font-size: 16px;
    margin-top: 4px;
    margin-left: 3px;
  }
  .avatar {
    display: none;
  }
  .right {
    margin-left: 10px;
    margin-right: 0px;
  }
}
</style>
