<template>
    <div class="leftComoponent col-md-6 r1 card col-sm-6">

  <div class="card-body r1">
         <h1 style="width: 80rem;"> wish you a many more happy returns of the day
           wish you a many more happy returns of the day
           wish you a many more happy returns of the day
           wish you a many more happy returns of the day
           wish you a many more happy returns of the day
           wish you a many more happy returns of the day
           wish you a many more happy returns of the day
         </h1>
          </div>
          <!-- <div class="r2">on the way</div> -->
          <!-- <div class="circle">
            I am the one
          </div>
          <div class="element">
            here I am
          </div> -->

    </div>
</template>
<script>

export default {
     name: 'TheLeftView',
}
</script>
<style >
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css");

.leftComoponent {
  padding: 50px 10px 50px 20px;
  /* border: 2px solid #f76707; */
  /* border-radius: 5px; */
  /* background-color: #c2c5eb; */
  /* display: grid; */
  /* grid-template-columns: 1fr 2fr; */
  /* grid-template-rows: repeat(3, 100px); */
}
.element {  
  float: left;
  shape-outside: circle(30%);
  width: 200px;
  height: 200px;
  background-color: aqua;
}
/* .circle{
   width: 500px;
  height: 500px;
  line-height: 500px;
  border-radius: 50%;
  font-size: 50px;
  color: rgb(48, 192, 125);
  text-align: center;
  background: rgb(189, 34, 34)
} */
.r1{
  /* transform: rotate(-13deg); */
  position: relative;
    overflow-y: auto;
    max-height: 400px;
    padding: 15px;
}
.r2{
  transform: rotate(-30deg);
}
</style>
// out line colur 
// content senter
// content on heart