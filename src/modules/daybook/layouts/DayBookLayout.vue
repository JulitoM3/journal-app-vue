<template>
  <NavBar/>

  <div class="d-flex">
    <div class="col-4">
      <EntryList/>
    </div>
    <div class="col">
      <router-view/>
    </div>
  </div>
</template>

<script>
import {defineAsyncComponent} from "vue";

export default {
  name: "DayBookLayout.vue",
  components: {
    NavBar: defineAsyncComponent(() => import('../components/NavBar.vue')),
    EntryList: defineAsyncComponent(() => import('../components/EntryList.vue')),
  }
}
</script>

<style scoped>

</style>