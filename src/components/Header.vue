<template>
    <nav class="navbar navbar-default">
       <div class="container-fluid">
        <!-- Brand and toggle get grouped for better mobile display -->
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#"><span class="glyphicon glyphicon-console" aria-hidden="true"></span> Qblog</a>
        </div>

        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">首页 <span class="sr-only">(current)</span></a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">分类 <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="#">JAVA</a></li>
                <li><a href="#">DOCKER</a></li>
                <li><a href="#">LINUX</a></li>
                <!-- <li role="separator" class="divider"></li>
                <li><a href="#">Separated link</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">One more separated link</a></li> -->
              </ul>
            </li>
            <li><a href="#">关于</a></li>
          </ul>
          <!-- <form class="navbar-form navbar-left">
            <div class="form-group">
              <input type="text" class="form-control" placeholder="Search">
            </div>
            <button type="submit" class="btn btn-default">Submit</button>
          </form> -->
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#/login">登录</a></li>
            <li><button type="button" class="btn btn-default navbar-btn" @click = "toRegister()">注册</button></li>
          </ul>
        </div><!-- /.navbar-collapse -->
       </div><!-- /.container-fluid -->
    </nav>
</template>

<script>
import Login from './Login'
import Register from './Register'
export default {
  name: 'Header',
  data () {
    return {
      icpNum: '京ICP备19014671号'
    }
  },
  components: {
    Login,
    Register
  },
  methods: {
    toRegister: function () {
      alert('注册')
    }
  }
}
</script>
