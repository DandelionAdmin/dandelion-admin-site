<template>
  <div id="Comments"></div>
</template>

<script>
import "artalk/dist/Artalk.css";
import Artalk from "artalk";

export default {
  mounted() {
    if (Artalk) {
      new Artalk({
        el: "#Comments",
        pageKey: "", // 页面链接
        pageTitle: "", // 页面标题
        server: "https://artalk.coderlab.cn", // 后端地址
        site: "Gear4j Doc",
      });
    }
  },
};
</script>
