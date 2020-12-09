<template>
  <div class="yellow">
    <fa :icon="['fas', 'star']" />
    <fa :icon="['fas', 'star']" />
    <fa :icon="['fas', 'star']" />
    <fa :icon="['fas', 'star']" />
    <fa :icon="['far', 'star']" />
  </div>
</template>

<script>
export default {
  props: {
    location: String,
  },
};
</script>
<style>
.yellow > *{
  color: #fbc02e;
}
</style>
