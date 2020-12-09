<template>
  <b-button :variant="variant" :href="location">
    <slot> </slot>
  </b-button>
</template>
<script>
export default {
  props: {
    location: String,
    solid:Boolean,
  },
  computed:{
    variant(){
      return this.solid ? "orange" : "outline-orange"
    }
  }
};
</script>
<style>
.btn-outline-orange {
  border-color: #f4b284;
  color: #f78454;
  transition: all 0.5s;
}
.btn-outline-orange:hover {
  background-color: #f78454;
  color: white;
  border-color: #f78454;
}
.btn-orange {
   background-color: #f78454;
  color: white;
  border-color: #f78454;
}
</style>
