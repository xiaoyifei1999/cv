<template>
    <div>
        <el-container>
            <el-header>Header</el-header>
            <el-main>
                <mainContent></mainContent>
            </el-main>
        </el-container>
    </div>
</template>

<script>
import mainContent from '@/components/main'

export default {
  components: {
      mainContent,
  },
  // 定义属性
  data() {
    return {

    };
  },
  // 计算属性，会监听依赖属性值随之变化
  computed: {},
  watch: {},
  methods: {},
  // 生命周期 - 创建完成（可以访问当前this实例）
  created() {},
  // 生命周期 - 挂载完成（可以访问DOM元素）
  mounted() {},
  beforeCreate() {}, // 生命周期 - 创建之前
  beforeMount() {}, // 生命周期 - 挂载之前
  beforeUpdate() {}, // 生命周期 - 更新之前
  updated() {}, // 生命周期 - 更新之后
  beforeDestroy() {}, // 生命周期 - 销毁之前
  destroyed() {}, // 生命周期 - 销毁完成
  activated() {} // 如果页面有keep-alive缓存功能，这个函数会触发
};
</script>

<style lang='stylus' scoped>
</style>