<template>
  <div id="tab-bar">
   <slot></slot>
   </div>
</template>

<script>
export default {
  name: 'TabBar',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#tab-bar{
  display: flex;
  background-color: #E7EAED;

  position:fixed;
  left: 0;
  right: 0;
  bottom: 0;
  box-shadow:0 -4px 2px rgb(100, 100, 100 ,0.15);
}

</style>
