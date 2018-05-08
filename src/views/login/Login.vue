<template>
  <div class="out">
    <div class="login">
      <el-container>
        <el-main>
          <form @submit.prevent>
            <el-input
              placeholder="请输入用户名">
              <i slot="prefix" class="el-input__icon el-icon-search"></i>
            </el-input>
            <el-input
              placeholder="请输入密码">
              <i slot="prefix" class="el-input__icon el-icon-search"></i>
            </el-input>
            <div>
              <el-checkbox v-model="checked">自动登录</el-checkbox>
              <a href="" style="float: right;">忘记密码</a>
            </div>
            <div>
              <el-button type="primary">登录</el-button>
            </div>
            <div>
              其他方式登录
              <a href="#/user/register">注册账户</a>
            </div>
          </form>
        </el-main>
      </el-container>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      checked: true
    }
  }
}
</script>
<style scoped lang="scss">
  @import "login.scss";
</style>
