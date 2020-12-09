<template>
  <b-navbar variant="faded" type="light" class="stickey-top navbar-border">
    <div class="container">
      <b-navbar-brand href="./" class="p-3">
        <img
          class="logo"
          src="https://upload.cc/i1/2020/12/01/z84ZlL.png"
          alt="Kitten"
        />
      </b-navbar-brand>
      <b-form inline>
        <b-form-input
          id="inline-form-input-name"
          class="mb-2 mr-sm-2 mb-sm-0"
          placeholder="你的電話"
        ></b-form-input>

        <b-button variant="orange">聯繫</b-button>
      </b-form>
    </div>
  </b-navbar>
</template>

<style scoped>
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
