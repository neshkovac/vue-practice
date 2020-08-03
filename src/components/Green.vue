<template>
  <div>
    <slotGreen></slotGreen>
  </div>
</template>

<script>
import GreenSlot from "./slots/GreenSlot.vue";

export default {
  components: {
    slotGreen: GreenSlot
  }
}
</script>

<style scoped>
div {
  border: 1px solid green;
  background-color: lightgreen;
  padding: 30px;
  margin: 20px auto;
  text-align: center
}
</style>