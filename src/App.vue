<template>
<div>
  <Header/>
  <router-view/>
  <Footer/>
</div>
</template>

<script type="text/ecmascript-6">
import Header from './components/Header'
import Footer from './components/Footer'
export default {
name:'App',
components:{
  Header,
  Footer
}
}
</script>

<style lang="less" scoped>


</style>
