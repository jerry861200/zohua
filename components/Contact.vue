<template>
  <div>
    
    <div class="">
      <b-alert v-model="showDismissibleAlert" variant="success" dismissible show>
      電話：0929232210
    </b-alert>
      <b-button @click="showDismissibleAlert=true" variant="orange" class="f-bold btn-contact my-1">
      電話即時詢問
      </b-button>
    <!-- </b-button>
      <b-button variant="orange" class="f-bold btn-contact my-1" @click="alertPhone">電話即時詢問</b-button> -->

      <a href="https://lin.ee/XwGVgkX"><b-button variant="line" class="f-bold btn-contact" >
         Line即時詢問</b-button
      ></a>
      
    </div>
  </div>
</template>

<style>
  .btn-line {
  background-color: #33c02b;
  color: white;
  border-color: #33c02b;
  transition: all 0.5s;
}
.btn-line:hover {
  background-color: #5fd35a;
  border-color: #5fd35a;
  color: white;
}
.f-bold{
  font-weight: 800;
}
.btn-orange {
  background-color: #f78454;
  color: white;
  border-color: #f78454;
  transition: all 0.5s;
}
.btn-orange:hover {
  background-color: #f4b284;
  border-color: #f4b284;
  color: white;
}
</style>

<script>
export default {
  data(){
    return{
      showDismissibleAlert:false,
    }
  },
  methods:{
    alertPhone(){
      alert('0929232210');
    }
  },
};
</script>
