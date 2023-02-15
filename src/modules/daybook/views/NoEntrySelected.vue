<template>
  <div class="d-flex justify-content-center">
    <h1 class="align-self-center">No have anything select</h1>
  </div>

  <fab/>
</template>

<script>
import { defineAsyncComponent } from 'vue';


export default {
  components:{
    Fab: defineAsyncComponent( () => import('../components/Fab.vue'))
  }
};
</script>


<style scoped>
div {
  height: 100%;
}
</style>
