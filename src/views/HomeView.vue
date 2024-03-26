<template>
  <div>
    <div>测试一下</div>
    <el-button @click="handleClick">点我一下</el-button>
    <div>
      <MapDemo></MapDemo>
    </div>
  </div>
</template>

<script>
import MapDemo from '@/views/mapDemo.vue'
export default {
  components: {
    MapDemo,
  },
  methods: {
    handleClick(){
      console.log("测试一下捏");
    },
  }, 

}
</script>

<style>

</style>