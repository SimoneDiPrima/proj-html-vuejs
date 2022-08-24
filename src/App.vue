<template>
<div>
  <BaseHeader />
  <BaseMain />
  <BlogSection /> 
  <ForumIconSection />
  <ForumSection/>
  <LastJumbotron />
 
</div>
 
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import BlogSection from './components/BlogSection.vue';
import ForumSection from './components/ForumSection.vue'
import ForumIconSection from './components/ForumIconSection.vue'
import LastJumbotron from './components/LastJumbotron.vue';
export default {
  name: 'App',
  components: {
    BaseHeader,BaseMain,BlogSection,ForumSection,ForumIconSection,LastJumbotron
  }
}
</script>

<style lang="scss">
@import './assets/scss/style.scss';


</style>
