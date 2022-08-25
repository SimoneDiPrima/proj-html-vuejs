<template>
  <div>
    <div class="lightblue">
     <div class="container d-flex justify-content-between align-items-center">
        <div>
          <img src="./assets/avadaImages/logo.png" alt="">
        </div>
        <div class="d-flex">
          <BaseHeader  v-for="(linkHeader,i) in headerItems" :key="i" :headerMenu ="linkHeader"   />
          <button class="buttonHeader ms-2 bg-dark text-white">JOIN US<i class="fa-solid fa-chevron-right"></i></button>
        </div>
      </div>

    </div>
  
  
    <BaseMain />
    <BlogSection /> 
    <ForumIconSection />
    <ForumSection />
    <LastJumbotron />
    <NewsletterSection />
    <div class="d-flex offset-1 col-9 mt-5">
      <BaseFooter class="col-3" v-for="(link,i) in FooterListItems" :key="i" :footerList="link" />
    </div>
 
  </div>
 
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import BlogSection from './components/BlogSection.vue';
import ForumSection from './components/ForumSection.vue'
import ForumIconSection from './components/ForumIconSection.vue'
import LastJumbotron from './components/LastJumbotron.vue';
import NewsletterSection from './components/NewsletterSection.vue';
import BaseFooter from './components/BaseFooter.vue';
import BaseMessageFooter from './components/BaseMessageFooter.vue'
export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BlogSection,
    ForumSection,
    ForumIconSection,
    LastJumbotron,
    NewsletterSection,
    BaseFooter,
    BaseMessageFooter
}, data(){
        return{ 
          headerItems : [
            {text:'apple',url:'#',current:false},
            {text:'microsoft',url:'#',current: false},
            {text:'android',url:'#',current: false,},
            {text:'forum',url:'#',current: false,},
            {text:'contact us',url:'#',current: false,}
            ],
            FooterMessage:{
                title:'TECH FORUM',
                item:'sed semper, nisi id feugiat eleifend,erat est digissim fetis,quis auctor elit enim nec ante, cras et nibh risus,Pelientesque non mi sit amet mi intermentum'
            },
            FooterListItems:[
                {title:'POPULAR TOPICS',
                firstItem:'Nam a dolor voluptat massa autor semper',
                secondItem:'Sed euismod nunc urna fermentum arcu dapibus fringilla',
                thirdItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                lastItem:'Curabitur a scellerisque ligula'
                },
                {title:'RECENT TOPICS',
                firstItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                secondItem:'Proin at ligula saggittis vestibulum nisi vitae',
                thirdItem:'Sed nec metus at est tincidunt elementum',
                lastItem:'Nulla egestas nulla eu nulla suscipit molestie'
                },
                {title:'LATEST REPLIES',
                firstItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                secondItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                thirdItem:'Nulla egestas nulla eu nulla suscipit molestie',
                lastItem:'Mauris ac nibh quis eros saggittis lacinia a et dui'
                },
                ]
        }
    }
}
</script>

<style lang="scss">
@import './assets/scss/style.scss';

.lightblue{
  background-color: #27aabe;
max-width:100%;
}
.buttonHeader{
    width:100px;
   height:30px;
   margin-top:35px;
   text-align:center;
}

</style>
