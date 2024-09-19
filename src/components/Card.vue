<template>
  <div>
    <h2>B3</h2>
    <div class="Image">
        <p class="image">Image</p>
    </div>
    <div class="Title">
        <p class="title">Title</p>
    </div>
    <button class="btn">Add to card</button>
  </div>
</template>

<script>

</script>

<style>
.Image {
    background: grey;
    width: 150px;
    height: 80px;
    border-top-left-radius: 4%;
    border-top-right-radius: 4%;
    display: flex; /* Sử dụng flexbox ở đây */
    justify-content: center; /* Căn giữa theo chiều ngang */
    align-items: center; /* Căn giữa theo chiều dọc */
}
.Title {
    border: 0.5px solid black;
    width: 150px;
    height: 80px;
    border-bottom-left-radius: 4%;
    border-bottom-right-radius: 4%;
    display: flex; /* Sử dụng flexbox ở đây */
    justify-content: center; /* Căn giữa theo chiều ngang */
   
}
.btn{
    position: absolute;
    margin-top: -30px;
    margin-left: 30px;
}
</style>
