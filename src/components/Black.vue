<template>
  <div>
	  <slot></slot>
  </div>
</template>

<script>

</script>

<style scoped>
  .label {
    fill: black;
  }
  .bottle, .wine-text {
    fill: white;
  }
  .flor {
    fill: #ccc;
  }
  .bkimg {
    filter:url(#inverse)
  }
</style>