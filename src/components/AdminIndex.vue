<template>
  <div class="body">
    <Header></Header>
    <div class="body-1">
      <Menu></Menu>
      <div class="body-2">
        <Main></Main>
        <Footer></Footer>
      </div>
    </div>
  </div>
</template>

<script setup>
import Header from "./bt07/Header.vue";
import Footer from "./bt07/Footer.vue";
import Menu from "./bt07/Menu.vue";
import Main from "./bt07/Main.vue";
</script>

<style scoped>
.body {
  display: flex;
  flex-direction: column;
}
.body-1 {
  display: flex;
  flex-direction: row;
}
.body-2 {
  display: flex;
  flex-direction: column;
}
</style>