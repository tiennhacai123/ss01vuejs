<template>
  <div class="body">
    <Header></Header>
    <Navigation></Navigation>
    <div class="body-1">
      <Menu></Menu>
      <Main></Main>
      <Article></Article>
    </div>
  </div>
</template>

<script setup>
import Header from "./bt08/Header.vue";
import Navigation from "./bt08/Navigation.vue";
import Menu from "./bt08/Menu.vue";
import Article from "./bt08/Article.vue";
import Main from "./bt08/Main.vue";
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
</style>