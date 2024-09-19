<template>
  <div class="container">
    <h2>b2</h2>
    <p class="box1">box</p>
    <p class="box2">box</p>
    <p class="box3">box</p> 
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
  display: flex;
  align-items: center;
  flex-direction: row;
  gap: 10px
}

.box1, .box2, .box3 {
  width: 200px;
  height: 200px;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white; 
}

.box1 {
  background-color: red;
}

.box2 {
  background-color: blue;
}

.box3 {
  background-color: green;
}
</style>
