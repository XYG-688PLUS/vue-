<template>
    <el-row>
        <el-col :span="12"><div class="grid-content bg-purple">
            这里是搜索列布局
            </div></el-col>
        <el-col :span="12"><div class="grid-content bg-purple-light">
这里是操作布局
        </div></el-col>
    </el-row>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Table',
  components: {
  },
  data(){
      return{
           
      }
  }
}
</script>
<style>
 .el-row {
    margin-bottom: 20px;
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 20px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>