<template>
    <div class="leftComoponent col-md-6 col-sm-6">
        <h1>here from left side</h1>
    </div>
</template>
<script>
export default {
     name: 'TheLeftView',
}
</script>
<style scoped>
.leftComoponent {
  padding: 20px 10px 20px 20px;
  /* border: 2px solid #f76707; */
  /* border-radius: 5px; */
  background-color: #c2c5eb;
  -ms-transform: skewY(0deg); /* IE 9 */
  transform: skewY(-40deg);
  /* display: grid; */
  grid-template-columns: 1fr 2fr;
  grid-template-rows: repeat(3, 100px);
}
</style>