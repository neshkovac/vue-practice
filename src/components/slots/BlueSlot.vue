<template>
  <div>
   <slotBlueInside :slotColor="slotColor"></slotBlueInside>
  </div>
</template>

<script>
import SlotBlueInside from './slot-inside/BlueSlotInside.vue'
export default {
  data: function () {

    return {
      slotColor: 'blue'
    }
  },
  components : {
    slotBlueInside: SlotBlueInside
  }
}
</script>

<style scoped>
h2 {
  color: blueviolet;
  font-size: 25px;
}

p {
  color: blue;
  font-size: 12px;
}
</style>