<script setup lang="ts">
import { RouterLink } from 'vue-router'

</script>


<template>
<div class="topnav">
  <RouterLink  :to="{name: 'home'}">Namai</RouterLink>
  <RouterLink :to="{name: 'grader'}">Įsivertinti</RouterLink>
  <a >Contact</a>
  <a >About</a>
</div>
</template>



<style scoped>
.topnav {
  background-color: #333;
  overflow: hidden;
  width: 100%;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}



</style>