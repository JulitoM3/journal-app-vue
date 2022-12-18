<template>
  <button
      class="btn btn-primary"
  >
    <i :class="icon"></i>
  </button>
</template>

<script>
export default {
  name: "FAB",
  props:{
    icon:{
      type:String,
      default: 'fa fa-2x fas fa-plus'
    }
  }
}
</script>

<style lang="scss" scoped>
button{
  position: fixed;
  bottom: 20px;
  right: 20px;
  width: 80px;
  height: 80px;
  border-radius: 100%;
}
</style>