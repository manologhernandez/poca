<template>
  <div class="container">
    <div class="row row-cols-8 no-gutters">
      <div class="col-sm" v-for="index in 8" :key="index">
        <PocaSmall />
      </div>
    </div>
  </div>
</template>

<script>
import PocaSmall from './PocaSmall.vue'
export default { components: { PocaSmall } }
</script>

<style scoped></style>
