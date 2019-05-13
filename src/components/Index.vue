<template>
    <div class="container">
      <div class="row">
        <div class="col-sm-8">
          <div class="jumbotron text-center">
            <h3>某人的博客</h3>
            <p>树欲静而风不止</p>
          </div>
          <ArticleList></ArticleList>
        </div>
        <div class="col-sm-4">
          <UserInfo></UserInfo>
          <Group></Group>
        </div>
      </div>
    </div>
</template>
<script>
import Group from './Group'
import ArticleList from './ArticleList'
import UserInfo from './UserInfo'
export default {
  name: 'Index',
  components: {
    Group,
    ArticleList,
    UserInfo
  }
}
</script>
