<template>
  <div class="container">
    <h1 class="unstoppable-text">Unstoppable</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .container h1 {
    color: black;
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    filter: drop-shadow(0px 3px 2px rgba(0, 0,0, .1));
  }

  .unstoppable-text {
    background: linear-gradient(45deg, #B019EB 0%, #F7CB70 57%, #2BFF88 90%);
  }
</style>
