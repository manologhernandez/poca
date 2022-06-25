<template>
  <div class="pocawall">
    <div v-for="rowindex in 3" :key="rowindex" class="row no-gutter poca-row">
      <div v-for="index in 12" :key="index" class="col-sm-1">
        <PocaSmall />
      </div>
    </div>
  </div>
</template>

<script>
import PocaSmall from './PocaSmall.vue'
export default { components: { PocaSmall } }
</script>

<style scoped>
.pocawall {
  padding: 15px;
}
</style>
