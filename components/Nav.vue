<template>
  <b-navbar variant="faded" type="light" class="stickey-top navbar-border">
    <div class="container">
      <img class="logo" src="../assets/img/logo-1.png" alt="Kitten" />
      <div class="ml-auto mr-3">
        <h4 class="contact-title m-2 mt-3">
          讓我們幫你推薦最適合的店家!
          </h4>   
        <Contact/>
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

.contact-title{
  color: #6d6d6d;
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
.avatar-container {
  overflow-x: hidden;
}
.avatar {
  width: auto;
  height: 100px;
}
.btn{
    width: 8em;
    height: auto;
    font-size: 25px;
}
</style>
