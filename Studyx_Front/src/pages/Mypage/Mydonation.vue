<template>
  <div>
    <el-breadcrumb separator="/" style="margin-top: 40px; margin-left: 350px;height:40px;">
        <el-breadcrumb-item :to="{ path: '/user' }">我的页面</el-breadcrumb-item>
        <el-breadcrumb-item
          ><a href="/user/mydonation">我的捐赠</a></el-breadcrumb-item
        >
      </el-breadcrumb>
  </div>
</template>

<script>

export default {

};
</script>

<style scoped>
</style>