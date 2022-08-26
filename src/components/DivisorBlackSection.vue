<template>
    <div class="DivisorHeight bg-dark text-center">
        <div class="container">
           <h6 class="lh-100 fw-bold p-2 text-white">{{title}}<i class="fa-solid fa-arrow-right"></i></h6> 
        </div>
    </div>

</template>
<script>
export default{
    name:'DivisorBlackSection',
    props:{
        title:String
    }
}

</script>
<style lang="scss">
@import '../assets/scss/style.scss';
.DivisorHeight{
    height:100px;
}
.lh-100{
    line-height:100px;
}
.iconF{
    color:$color_White;
}
    
</style>