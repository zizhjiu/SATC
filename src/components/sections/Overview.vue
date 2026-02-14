<script setup>
import abstract from '../mds/abstract.mdx';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <el-col
        :xs="24"
        :sm="20"
        :md="16"
        :lg="12"
        :xl="12"
        class="abstract-container"
      >

        <!-- 架构图 -->
        <div class="figure-box">
          <el-image
            src="/structure.jpg"
            fit="contain"
            class="figure-img"
          />
          <div class="figure-caption">
            Figure 1: Overview of the proposed framework.
          </div>
        </div>

        <!-- 删除 abstract -->
        <!-- <abstract /> -->

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

/* 图片整体居中 */
.figure-box {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 30px 0;
}

/* 图片大小可控 */
.figure-img {
  max-width: 100%;
}

/* caption 居中 + 论文风格 */
.figure-caption {
  margin-top: 8px;
  text-align: center;
  font-size: 18px;
  color: #555;
}
</style>
