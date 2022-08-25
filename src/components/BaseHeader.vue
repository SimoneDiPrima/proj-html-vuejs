<template>
<div class="lightblue">
    <header class="container text-white">
    <nav class="d-flex justify-content-between align-items-center">
        <div>
            <img src="../assets/avadaImages/logo.png" alt="">
        </div>
        <div class="d-flex mt-3">
            <ul class="d-flex lh-70">
                <li class="me-2" v-for="(item,i) in headerItems" :key="i">
                    <a :href="item.url" class="pippo" :class="{ current : item.current }">{{item.text}}</a>
                </li>
            </ul>
            <button class="buttonHeader bg-dark text-white">JOIN US<i class="fa-solid fa-chevron-right"></i></button>
        </div>
      
        
    </nav>
   
  </header>

  </div>
</template>
<script>
export default{
    name:'BaseHeader',
   
    data(){
        return{
            headerItems : [
            {text:'apple',url:'#',current:false},
            {text:'microsoft',url:'#',current: false},
            {text:'android',url:'#',current: false,},
            {text:'forum',url:'#',current: false,},
            {text:'contact us',url:'#',current: false,}
            ]
        }
    },
    

}
</script>
<style lang="scss">
@import '../assets/scss/style.scss';
.lh-70{
    line-height:70px;
}
.buttonHeader{
    width:100px;
   height:50px;
   margin-top:10px;
   text-align:center;
}

li{
  list-style-type:none;
}
li a{
    color:white;
    text-decoration: none;
  &.current,
  &:hover{
    text-decoration: underline orange ;
    color:white;
  }
}
.lightblue{
  background-color: #27aabe;
}
</style>