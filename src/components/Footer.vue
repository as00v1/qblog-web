<template>
    <footer>
      <p class="text-center">www.qiaohx.com</p>
      <p class="text-center">{{ icpNum }}</p>
    </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      icpNum: '京ICP备19014671号'
    }
  }
}
</script>

<style>
/* footer {
    text-align: center;
} */
</style>
