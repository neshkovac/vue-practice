<template>
  <div>
    <slot>
      <h2>This is the {{ slotColor }} slot!</h2>
      <p>{{ slotColor }} slot description!</p>
    </slot>
  </div>
</template>

<script>
export default {
  props: ['slotColor']
}
</script>

<style scoped>

</style>