<template>
    <div class="Blog bg-dark text-center">
        <div class="container">
           <h6 class="lh-100 fw-bold p-2 text-white">{{title}}<i class="fa-solid fa-arrow-right"></i></h6> 
        </div>
    </div>

</template>
<script>
export default{
    name:'BlogSection',
    data(){
        return{
            array:['GO TO OUR FORUM','GO TO OUR BLOG']
        }
    },
    props:{
        title:Array
    }
}

</script>
<style lang="scss">
@import '../assets/scss/style.scss';
.Blog{
    height:100px;
}
.lh-100{
    line-height:100px;
}
.iconF{
    color:white;
}
    
</style>