<template>
  <v-scale-screen :width="1920" :height="1080">
    <div style="height: 100%; width: 100%">
      <el-config-provider :locale="zhCn">
        <Screen />
      </el-config-provider>
    </div>
  </v-scale-screen>
</template>
<script setup lang="ts">
import Screen from "@/Layout/Screen.vue";
import VScaleScreen from "v-scale-screen";
import { ElConfigProvider } from "element-plus";
import zhCn from "element-plus/dist/locale/zh-cn.mjs";
</script>
