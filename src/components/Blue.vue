<template>
    <div>
        <slotBlue></slotBlue>
    </div>
</template>

<script>
import BlueSlot from "./slots/BlueSlot.vue";

export default{
  data: function(){
    return {

    }
  },
  components: {
    slotBlue : BlueSlot
  }
}

</script>

<style scoped>
    div {
        border: 1px solid blue;
        background-color: lightblue;
        padding: 30px;
        margin: 20px auto;
        text-align: center
    }
</style>