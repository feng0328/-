<template>
  <el-container class="container">
    <el-header>Header</el-header>
    <el-container>
      <el-aside class="aside" width="200px">Aside</el-aside>
      <el-main class="main">Main</el-main>
    </el-container>
  </el-container>
</template>

<script>
export default {}
</script>

<style>
.container {
    background-color: yellow;
    height: 100%;
}
.aside {
    background-color: red;
}
.main {
    background-color: blue;
}
</style>
