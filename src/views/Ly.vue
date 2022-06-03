<template>
  <div id="app">
      <div class="box">
          <el-container>
            <el-aside width="200px">这里是选项卡组</el-aside>
            <el-container>
                <el-header>
                    这里是用户信息
                </el-header>
                <el-main>
                    <serach></serach>
                    <Table></Table>
                </el-main>
            </el-container>
        </el-container>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Table from '../components/table.vue'
import serach from '../components/seach.vue'
export default {
  name: 'ly',
  components: {
      Table,
      serach
  }
}
</script>
<style>
.el-header, .el-footer {
    background-color: #B3C0D1;
    color: #333;
    text-align: center;
    line-height: 60px;
  }
  
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }
  
  .el-main {
    background-color: #E9EEF3;
    color: #333;
    text-align: center;
    line-height: 160px;
  }
  
  body > .el-container {
    margin-bottom: 40px;
  }
  
  .el-container:nth-child(5) .el-aside,
  .el-container:nth-child(6) .el-aside {
    line-height: 260px;
  }
  
  .el-container:nth-child(7) .el-aside {
    line-height: 320px;
  }
  html,body{
  height: 100%;
}
#app, .box{
  height:100%;
}
.el-container{
  height: 100%;
}
</style>