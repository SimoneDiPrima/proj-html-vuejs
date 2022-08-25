<template>
<!-- ultima sezione jumbotron collegata alla newsletter -->
<div id="lastJumbotron" class="py-4">
    <div class="offset-4 col-4 pt-5 text-white">
        <h1 class="text-center">Hey! Join to our community!</h1>
        <p class="text-center">Nulla molestie tortor nec lectus venenatis, sed blandit duit finibus.curabitur feugeat vuluptate purus
            ipsums dolores ficilis uns etra
        </p>
        <button class="BackGray offset-4 col-4 text-white">
            SIGN UP <i class="fa-solid fa-chevron-right"></i>
        </button>
    </div>
</div>


</template>
<script>
export default{
    name:'LastJumbotron',
}

</script>
<style lang="scss" scoped>
@import '../assets/scss/style.scss';
img{
   max-width:100%;
}
#lastJumbotron{
    background-image: url('../assets/avadaImages/join_now_cta_bg.jpg');
    background-position: center;
}
.BackGray{
  background-color: #4A4A4A;
}
    
</style>