<template>
  <svg  class="g-icon">
    <use :xlink:href=`#i${name}`></use>
  </svg>
</template>

<script lang="ts">
  export default {
    props:{
      name:{
        type:String
      }
    }
  };
</script>

<style lang="scss" scoped>
   .g-icon {
    order: 1;
    margin-right: .1em;
  }
</style>