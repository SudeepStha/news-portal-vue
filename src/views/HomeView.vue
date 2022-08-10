<template>
  <div>
    <top-view/>
    <header-components/>
    <nav-bar/>
    <article-view/>

  </div>
</template>

<script>
import TopView from '@/components/TopView.vue'
import HeaderComponents from '@/components/HeaderComponents.vue'
import NavBar from '@/components/NavBar.vue'
import ArticleView from '@components/ArticleView.vue'

export default {
  components:{
    TopView,
    NavBar,
    HeaderComponents,
    ArticleView,
    }
}
</script>
