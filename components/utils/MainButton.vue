<template>
  <b-button variant="outline-purple" :href="location">
    <slot> </slot>
  </b-button>
</template>
<script>
export default {
  props: {
    location: String,
  },
};
</script>
<style>
.btn-outline-purple {
  border-color: #cbc9fc;
  color: #6558f6;
  transition: all 0.5s;
}
.btn-outline-purple:hover {
  background-color: #6558f6;
  color: white;
  border-color: #6558f6;
}
</style>
