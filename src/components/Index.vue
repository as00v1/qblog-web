<template>
    <div class="container">
      <div class="row">
        <div class="col-8">
            <ArticleList></ArticleList>
        </div>
      </div>
      <div class="row">
        <div class="col-4">
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
