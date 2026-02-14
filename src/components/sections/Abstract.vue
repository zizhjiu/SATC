<script setup>
import abstract from '../mds/abstract.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
        <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12" class="abstract-container">
            <abstract />
        </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.abstract-container {
  text-align: justify;
  line-height: 1.75;
  font-size: 15px;
}

</style>