<template>
  <div>
    <slotGreenInside :slotColor="slotColor"></slotGreenInside>
  </div>
</template>

<script>
import SlotGreenInside from './slot-inside/GreenSlotInside.vue';

export default {
  data: function () {
    return {
      slotColor: 'green'
    }
  },
  components: {
    slotGreenInside: SlotGreenInside
  }
}
</script>

<style scoped>
h2 {
  color: darkgreen;
  font-size: 25px;
}

p {
  color: green;
  font-size: 12px;
}
</style>