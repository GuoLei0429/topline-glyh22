<template>
  <el-row class="app-header">
    <el-col :span="14">尹航是个大傻子哈哈哈哈哈</el-col>
    <el-col :span="10">
      <!-- trigger="click"点击激活 -->
      <el-dropdown trigger="click">
        <span class="el-dropdown-link">
           <img width="30px" src="http://b-ssl.duitang.com/uploads/item/201712/22/20171222223729_d8HCB.jpeg">
          15522888637
          <i class="el-icon-arrow-down el-icon--right"></i>
        </span>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item>账户设置</el-dropdown-item>
          <el-dropdown-item>退出</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: 'AppHeader',
  data () {
    return {}
  }
}
</script>

<style lang="less" scoped>
.app-header {
  height: 60px;
  display: flex;
  align-items: center;
}

.el-dropdown-link {
  // 设置小手
  cursor: pointer;
  color: #409eff;
}

.el-icon-arrow-down {
  font-size: 12px;
}

img {
  border-radius: 50%;
  text-align: left;
}
</style>
