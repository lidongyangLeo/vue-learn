<template>
  <div>
    <el-button type="primary" size="default" :icon="Plus">button</el-button>
    <el-button type="success" size="large" :icon="Edit">
      success button
    </el-button>
    <el-button type="danger" size="small" :icon="Delete">
      delete button
    </el-button>
  </div>
</template>
<script setup lang="ts">
import { Delete, Edit, Plus } from '@element-plus/icons-vue'
</script>

<style scoped></style>
