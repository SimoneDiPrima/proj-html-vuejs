<template>
    <div class="BackGray">
        <header class="container text-white">
            <nav>
                <div class="mt-3">
                    <ul class="lh-70">
                        <li>
                            <a :href="headerMenu.url" class="d-flex" :class="{ current : headerMenu.current }">{{headerMenu.text}}</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </header>
    </div>
</template>
<script>
export default{
    name:'BaseHeader',
   

    props:{
        headerMenu:Object
    }
    

}
</script>
<style lang="scss">
@import '../assets/scss/style.scss';
.lh-70{
    line-height:70px;
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
.BackGray{
  background-color: #4A4A4A;
}
</style>