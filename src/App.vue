
<script setup>
import ColorBox from "./components/ColorBox.vue";
import ListCourse from "./components/ListCourse.vue";
import Card from "./components/Card.vue";
import Calculation from "./components/Calculation.vue";
import UserInfo from "./components/UserInfo.vue";
import FormatName from "./components/FormatName.vue";
import AdminIndex from "./components/AdminIndex.vue";
import UserLayout from "./components/UserLayout.vue";
import ManagerUser from "./components/ManagerUser.vue";
import TodolistIndex from "./components/TodolistIndex.vue";
</script>

<template>
<div>
  <ListCourse/>
  <ColorBox/>  
  <Card/>
  <Calculation/>
  <UserInfo/>
  <FormatName/>
  <AdminIndex></AdminIndex>
    <br />
    <UserLayout></UserLayout>
    <br />
    <ManagerUser></ManagerUser>
    <br />
    <TodolistIndex></TodolistIndex>
</div>

</template>



<style scoped>
/* noi de css  SU DUNG SCOPEd de cho cac css ko bi mau thuan*/


</style>