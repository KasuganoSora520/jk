<template>
  <el-form ref="form" :model="form" label-width="80px">
    <el-form-item label="活动名称">
      <el-input v-model="form.name"></el-input>
    </el-form-item>
    <el-form-item label="活动名称">
      <el-input v-model="form.name"></el-input>
    </el-form-item>
  </el-form>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style>
</style>
