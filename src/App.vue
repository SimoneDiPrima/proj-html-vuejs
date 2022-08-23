<template>
<div>
  <BaseHeader />
  <BaseMain />
  <BlogSection /> 
 
</div>
 
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import BlogSection from './components/BlogSection.vue';
export default {
  name: 'App',
  components: {
    BaseHeader,BaseMain,BlogSection,
  }
}
</script>

<style lang="scss">
@import './assets/scss/style.scss';


</style>
