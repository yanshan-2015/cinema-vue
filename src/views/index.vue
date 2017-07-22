<template>
  <div class="index">
    <p>重新开始搭建一个项目·{{title.name}}</p>
    <my-head></my-head>
    <my-footer></my-footer>
  </div>
</template>
<script>
  import MyHead from '@/components/head.vue'
  import MyFooter from '@/components/footer.vue'
  export default{
    name: 'index',
    components: { MyHead, MyFooter },
    data() {
        return{
            title: {
                name: '白哲'
            }
        }
    }
  }
</script>

<style lang="less" scoped>
  .index{

  }
</style>
