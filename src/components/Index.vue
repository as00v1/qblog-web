<template>
    <div class="container">
        <div class="col-sm-6 col-md-8">
            <ArticleList></ArticleList>
        </div>
        <div class="col-sm-6 col-md-4">
            <UserInfo></UserInfo>
            <Group></Group>
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
