<template>
  <div>
    <div class="BackGray">
      <div class="container d-flex justify-content-between align-items-center">
        <BaseLogo />
        <div class="d-flex align-items-center">
          <BaseHeader  v-for="(linkHeader,i) in headerItems" :key="i" :headerMenu ="linkHeader"   />
          <button class="buttonHeader ms-2 bg-dark text-white">JOIN US<i class="fa-solid fa-chevron-right"></i></button>
          <i class="text-white ms-2 fa-solid fa-magnifying-glass"></i>
        </div>
      </div>
    </div>
    <BaseMain />
    <DivisorBlackSection title="GO TO OUR BLOG " />
    <ForumIconSection />
   <DivisorBlackSection title="GO TO OUR FORUM "/>
    <LastJumbotron />
    <NewsletterSection/>
    <div class="container d-flex justify-content-around offset-1 col-9 my-5">
      <BaseMessageFooter/>
      <BaseFooter class="col-3" v-for="(link,i) in FooterListItems" :key="i" :footerList="link" />
    </div>
 
  </div>
 
</template>

<script>
import BaseLogo from './components/BaseLogo.vue';
import BaseHeader from './components/BaseHeader.vue';
import BaseMain from './components/BaseMain.vue';
import ForumIconSection from './components/ForumIconSection.vue'
import LastJumbotron from './components/LastJumbotron.vue';
import NewsletterSection from './components/NewsletterSection.vue';
import BaseFooter from './components/BaseFooter.vue';
import BaseMessageFooter from './components/BaseMessageFooter.vue'
import DivisorBlackSection from './components/DivisorBlackSection.vue';
export default {
  name: 'App',
  components: {
    BaseLogo,
    BaseHeader,
    BaseMain,
    ForumIconSection,
    LastJumbotron,
    NewsletterSection,
    BaseFooter,
    BaseMessageFooter,
    DivisorBlackSection,
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
   text-align:center;
}
.BackGray{
  background-color: #4A4A4A;
}
</style>
