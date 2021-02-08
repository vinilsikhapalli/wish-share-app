<template>
  <div class="header">
        <h1>from Header</h1>
  </div>
</template>

<script>
export default {
  name: 'TheHeader',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .header {
  padding: 20px 30px 20px 30px;
  /* border: 2px solid #f76707; */
  background-color: #8ebfe7;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(2, 100px);
}

</style>
