<template>
  <div class="login_container">
    <div class="login_box">
      <div class="avatar_box">
        <img src="../assets/logo.png" />
      </div>
      <el-form  label-width="0px">
        <el-form-item>
            <el-input></el-input>
        </el-form-item>
        <el-form-item>
            <el-input></el-input>
        </el-form-item>
        <el-form-item>
            <el-button type="primary">登录</el-button>
        </el-form-item>
        <el-form-item>
            <el-button type="info">重置</el-button>
        </el-form-item>
        </el-form>
    </div>
  </div>
</template>
<script>
export default {
}
</script>
<style lang="less" scoped>
.login_container {
  height: 100%;
  background-color: gray;
  display: flex;
  justify-content: center;
  align-items: center;
}
.login_box {
  width: 450px;
  height: 300px;
  background-color: white;
  display: flex;
  justify-content: center;
}
.avatar_box {
  height: 130px;
  width: 130px;
  border: 1px solid #eee;
  border-radius: 50%;
  padding: 10px;
  box-shadow: 0 0 10px #add;
  position: absolute;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: white;
  img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background-color: #eee;
  }
}
</style>
