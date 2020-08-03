<template>
  <div>
      <slotRedInside :slotColor="slotColor"></slotRedInside>
  </div>
</template>

<script>
import RedSlotInside from "./slot-inside/RedSlotInside.vue";
export default {
  data: function () {
    return {
      slotColor: 'red'
    }
  },
  components: {
    slotRedInside: RedSlotInside
  }
}
</script>

<style scoped>
h2 {
  color: mediumvioletred;
  font-size: 25px;
}

p {
  color: firebrick;
  font-size: 12px;
}
</style>