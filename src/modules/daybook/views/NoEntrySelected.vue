<template>
<div class="d-flex justify-content-center">
  <h1 class="align-self-center">
    Nada seleccionado
  </h1>

  <FAB/>
</div>
</template>
<script>
import {defineAsyncComponent} from "vue";
export default {
  components:{
    FAB: defineAsyncComponent(()=>import('../components/FAB.vue'))
  }
}
</script>

<style lang="scss" scoped>
div{
  height: 100px;
}
</style>