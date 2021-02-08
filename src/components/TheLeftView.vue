<template>
    <div class="leftComoponent col-md-6 col-sm-6">
        <div class="heart-shape text-center col-6 ">
          <!-- <h2>hello world from here</h2> -->
        </div>
    </div>
</template>
<script>
export default {
     name: 'TheLeftView',
}
</script>
<style scoped>
.leftComoponent {
  padding: 50px 10px 50px 20px;
  border: 2px solid #f76707;
  /* border-radius: 5px; */
  background-color: #c2c5eb;
  /* display: grid; */
  /* grid-template-columns: 1fr 2fr; */
  /* grid-template-rows: repeat(3, 100px); */
}
.heart-shape{
  position: relative;
  width: 145px;
  height: 145px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
  transform: rotate(45deg);
  background-color: rgb(250, 66, 152);
}
.heart-shape:before,
.heart-shape:after{
  position: absolute;
  width: 145px;
  height: 145px;
  content: '';
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  -o-border-radius: 50%;
  border-radius: 50%;
  background-color: rgb(250, 66, 152);
}
.heart-shape:before{
  bottom: 0px;
  left: -50px;
}
.heart-shape:after{
  top: -50px;
  right: 0px;
}
</style>
// out line colur 
// content senter
// content on heart