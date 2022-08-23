<template>
    <div class="container">
        <h6 class="mare text-center">PHASELLUS EGET METUS</h6>
        <h1 class="text-center">FORUM SECTION</h1>
       
       
         <div class="my-3">
        <div class="offset-1 col-9 d-flex flex-wrap my-5 ">
            <figure class="ps-1 col-3 text-center">
                <i class="fa-brands fa-apple mb-2 IconSpecial"></i>
                <h6>News e community</h6>
            </figure>
             <figure class="col-3 text-center">
                <i class="fa-brands fa-apple mb-2 IconSpecial"></i>
                <h6>Apple Forum</h6>
            </figure>
             <figure class="col-3 text-center">
               <i class="fa-brands fa-windows mb-2 IconSpecial"></i>
                <h6>Microsoft Forum</h6>
            </figure>
             <figure class="col-3 text-center">
              <i class="fa-brands fa-android mb-2 IconSpecial"></i>
                <h6>Android Forum</h6>
            </figure>
             <figure class="col-3 text-center">
              <i class="fa-solid fa-mug-saucer mb-2 IconSpecial"></i>
                <h6>General Discussion</h6>
            </figure>
             <figure class="col-3 text-center">
                <i class="fa-brands fa-apple mb-2 IconSpecial"></i>
                <h6>App e Software</h6>
            </figure>
             <figure class="col-3 text-center">
                <i class="fa-brands fa-apple mb-2 IconSpecial"></i>
                <h6>Gadgets & Stuff</h6>
            </figure>
             <figure class="col-3 text-center">
                <i class="fa-brands fa-apple mb-2 IconSpecial"></i>
                <h6>Tutorials & Guides</h6>
            </figure>

          
        </div>
        
      </div>
        
       
    </div>

</template>
<script>
export default{
    name:'ForumIconSection',
}

</script>
<style lang="scss">
@import '../assets/scss/style.scss';
.mare{
    letter-spacing: 4px;
}
.forumBlock{
    height:500px;
    border:1px solid black;

}
.IconSpecial{
    height:50px;
    width:50px;
    line-height:50px;
    border-radius:50%;
    background-color: orangered;
    color:white;
}
    
</style>