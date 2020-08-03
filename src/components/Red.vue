<template>
    <div>
      <slotRed></slotRed>
    </div>
</template>

<script>
import RedSlot from "./slots/RedSlot.vue";
export default{
  components: {
    slotRed: RedSlot
  }
}
</script>

<style scoped>
    div {
        border: 1px solid red;
        background-color: lightcoral;
        padding: 30px;
        margin: 20px auto;
        text-align: center
    }
</style>