<template>
  <div id="app">
    <CommonHeader></CommonHeader>
    <router-view/>
    <CommonFooter></CommonFooter> 
  </div>
</template>

<script>
import CommonHeader from '@/components/CommonHeader.vue';
import CommonFooter from '@/components/CommonFooter.vue'
export default {
  components: {
    CommonHeader ,
    CommonFooter
  },
  data(){
    return{
      menuList:[
        {
          title:'电影',
          bgColor:'#e54847',
          name: 'movie',
          path: '/movie' 
        },{
          title: '音乐',
          bgColor: '#009688',
          name: 'music',
          path: '/music'
        },{
          title: '书籍',
          bgColor: '#795548',
          name: 'book',
          path: '/book'
        },{
          title: '美图',
          bgColor: '#3f51b5',
          name: 'photo',
          path: '/photo'
        }
      ]
    }
  }
}
</script>

<style lang="scss">

</style>
