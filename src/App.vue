<template>
  <div id="app">
    <img src="./assets/logo.png">
    <el-row>
      <el-button>默认按钮</el-button>
      <el-button type="primary">主要按钮</el-button>
      <el-button type="success">成功按钮</el-button>
      <el-button type="info">信息按钮</el-button>
      <el-button type="warning">警告按钮</el-button>
      <el-button type="danger">危险按钮</el-button>
    </el-row>
<<<<<<< HEAD

=======
    <el-row>
      <el-button>默认按钮</el-button>
      <el-button size="medium">中等按钮</el-button>
      <el-button size="small">小型按钮</el-button>
      <el-button size="mini">超小按钮</el-button>
    </el-row>
>>>>>>> 8b336f8fb0091fab0e8a13396456124153441a2c
    <el-row>
      <el-col :span="12"><div class="grid-content bg-purple-dark">1</div></el-col>
    </el-row>
    <el-row>
      <el-col :span="12"><div class="grid-content bg-purple">2</div></el-col>
      <el-col :span="12"><div class="grid-content bg-purple-light">3</div></el-col>
    </el-row>
    <el-row>
      <el-col :span="8"><div class="grid-content bg-purple">4</div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple-light">5</div></el-col>
      <el-col :span="8"><div class="grid-content bg-purple">6</div></el-col>
    </el-row>
    <el-row>
      <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple-light"></div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="6"><div class="grid-content bg-purple-light"></div></el-col>
    </el-row>
    <el-row>
      <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple-light"></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple-light"></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple"></div></el-col>
      <el-col :span="4"><div class="grid-content bg-purple-light"></div></el-col>
    </el-row>
    <i class="el-icon-edit" >2452</i>
    <i class="el-icon-share"></i>
    <i class="el-icon-delete" border-radius:30px></i>
    <el-button type="primary" icon="el-icon-search">搜索</el-button>

  </div>

</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
  .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
      border-radius: 500px;
    }
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #09a9bf;
  }
  .bg-purple {
    background: #73dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 200px;
    min-height: 36px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>
