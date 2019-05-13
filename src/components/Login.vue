<template>
    <div class="container">
        <div class="row">
            <div class="col-lg-4">
                <p></p>
                <p></p>
            </div>
            <div class="col-sm=12 col-lg-4">
                <h1 class="text-center">登录</h1>
                <form>
                    <div class="form-group">
                        <label for="loginCert">用户名</label>
                        <input type="text" class="form-control" id="loginCert" placeholder="请输入用户名">
                        <small class="form-text text-muted">用户名由字母或数字混合组成，16位以内</small>
                    </div>
                    <div class="form-group">
                        <label for="password">密码</label>
                        <input type="password" class="form-control" id="password" placeholder="请输入密码">
                        <small class="form-text text-muted">密码由特殊符号、字母或数字混合组成，20位以内</small>
                    </div>
                    <div class="text-center">
                        <button type="button" class="btn btn-primary btn-block">登录</button>
                    </div>
                    <div class="text-center">
                        <button type="button" class="btn btn-link">没有账号？立即注册>></button>
                    </div>
                </form>
            </div>
            <div class="col-lg-4"></div>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Login',
  components: {
  }
}
</script>
