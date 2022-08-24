<template>
    <div class="forumBlock">
        <div class="container">
            <h6 class="letterSpace pt-5 text-center">PHASELLUS EGET METUS</h6>
            <h1 class="text-center pb-5">FORUM SECTION</h1>
        
        
            <div class=" d-flex justify-content-center">
                <div class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                    <i class="fa-solid fa-file mb-1 IconSpecial"></i>
                        <h6>News e community</h6>
                    </figure>
                </div>
                <div  class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                        <i class="fa-brands fa-apple mb-1 IconSpecial"></i>
                        <h6>Apple Forum</h6>
                    </figure>
                </div>
                <div  class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                        <i class="fa-brands fa-microsoft mb-1 IconSpecial"></i>
                        <h6>Microsoft Forum</h6>
                    </figure>
                </div>
                <div  class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                        <i class="fa-brands fa-android mb-1 IconSpecial"></i>
                        <h6>Android Forum</h6>
                    </figure>
                </div>
            </div>
            <div class=" d-flex justify-content-center pb-5">
                <div class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                    <i class="fa-solid fa-mug-saucer mb-1 IconSpecial"></i>
                        <h6>General DIscussion</h6>
                    </figure>
                </div>
                <div  class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                        <i class="fa-brands fa-apple mb-1 IconSpecial"></i>
                        <h6>Apple Forum</h6>
                    </figure>
                </div>
                <div  class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                        <i class="fa-solid fa-laptop IconSpecial"></i>
                        <h6>Gadgets & Stuff</h6>
                    </figure>
                </div>
                <div  class="col-2 p-2">
                    <figure class="border-top border-primary bg-light fb-25 text-center p-5">
                        <i class="fa-brands fa-android mb-1 IconSpecial"></i>
                        <h6>Tutorials & Guides</h6>
                    </figure>
                </div>
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
.letterSpace{
    letter-spacing: 4px;
}
.forumBlock{
    background-color: #eee3d6;
}
.IconSpecial{
    height:50px;
    width:50px;
    line-height:50px;
    border-radius:50%;
    background-color: orangered;
    color:white;
}
.fb-25{
    flex-basis: 25%;
}
  
</style>