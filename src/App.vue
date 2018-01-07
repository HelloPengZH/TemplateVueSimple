<template>
  <div>
        <span class='red' v-text='name'>
          主页面App.Vue组件展示页面
        </span>
        <!-- app.vue页面主页面展示内容 -->
        <div>
          子组件展示页面展示页面
        </div>
        <div>
          子组件路由
        </div>
        <router-link to="/login">登录</router-link>
        <router-link to="/register">注册</router-link>
        <div>子组件展示</div>
        <router-view></router-view>
  </div>
</template>
<script>
export default {
  data(){
      return {
          name: '你好,try everything'
      }
    },
  methods:{

  },
  created(){

  }
}
</script>
<style scoped>
    .red {
       background-color: #213212 
    }
</style>

