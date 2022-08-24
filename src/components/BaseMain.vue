<template>
<div>
    <section class="bigImage">
    <img class="mw-100 position-relative" src="../assets/avadaImages/home_slider_bg.jpg" alt="">
    <div class="container position-absolute top-50 start-50 translate-middle text-start text-white">
      <h1 class="h1 titleBig fw-bold">Tech Forum!</h1>
      <p>Discuss all the latest technology news and trends</p>
      <button class="lightblue fs-5 text-white p-2">GET AVADA NOW! ></button>
    </div>
  </section>
  <section class="marginNegative text-center mt-3 bg-light">
    <h6 class="letterSpace">AVADA FORUM IS THE PLACE TO BE</h6>
    <p class="offset-3 col-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta nulla sunt unde eum excepturi odio perspiciatis ore sed sit, ipsum a nesciunt? Deserunt.Soluta nulla sunt unde eum excepturi odio perspiciatis ore sed sit, ipsum a nesciunt?</p>
  </section>
  <section class="marginNegative text-center mt-5 bg-light">
    <h6 class="letterSpace">PHASELLUS EGET METUS</h6>
    <h4 class="offset-3 col-6 fw-bolder">All the latest news</h4>
    <div class="text-warning mb-4">
      <hr class="offset-5 col-2">
    </div>
  </section>
  <section id="card">
    <div class="container">
      <div class="row d-flex justify-content-center">
        <figure class="col-3">
           <img src="../assets/avadaImages/post_feat_img_24-320x202.jpg" alt="">
           <h5>Morbi vitae dui euismud voluptate sollicitudin</h5>
           <p>Lorem ipsum dolor uam sequi quia, totam ipsum vero blanditiis accusantium sunt eligendi fugit. Quam inventore ab accusantium aliquid facilis temporibus!</p>
        </figure>
         <figure class="col-3">
           <img src="../assets/avadaImages/post_feat_img_25-320x202.jpg" alt="">
           <h5>Morbi vitae dui euismud voluptate sollicitudin</h5>
           <p>Lorem ipsum dolor uam sequi quia, totam ipsum vero blanditiis accusantium sunt eligendi fugit. Quam inventore ab accusantium aliquid facilis temporibus!</p>
        </figure>
         <figure class="col-3">
           <img src="../assets/avadaImages/post_feat_img_23-320x202.jpg" alt="">
           <h5>Morbi vitae dui euismud voluptate sollicitudin</h5>
           <p>Lorem ipsum dolor uam sequi quia, totam ipsum vero blanditiis accusantium sunt eligendi fugit. Quam inventore ab accusantium aliquid facilis temporibus!</p>
        </figure>
      </div>
      <div class="d-flex position-relative justify-content-center my-3">
        <figure class="col-9">
          <img src="../assets/avadaImages/featured_article_1_bg.jpg" alt="">
        </figure>
        
      </div>
      
       <div class="row d-flex justify-content-center">
        <figure class="col-3">
           <img src="../assets/avadaImages/post_feat_img_22-320x202.jpg" alt="">
           <h5>Morbi vitae dui euismud voluptate sollicitudin</h5>
           <p>Lorem ipsum dolor uam sequi quia, totam ipsum vero blanditiis accusantium sunt eligendi fugit. Quam inventore ab accusantium aliquid facilis temporibus!</p>
        </figure>
         <figure class="col-3">
           <img src="../assets/avadaImages/post_feat_img_21-320x202.jpg" alt="">
           <h5>Morbi vitae dui euismud voluptate sollicitudin</h5>
           <p>Lorem ipsum dolor uam sequi quia, totam ipsum vero blanditiis accusantium sunt eligendi fugit. Quam inventore ab accusantium aliquid facilis temporibus!</p>
        </figure>
         <figure class="col-3">
           <img src="../assets/avadaImages/post_feat_img_20-320x202.jpg" alt="">
           <h5>Morbi vitae dui euismud voluptate sollicitudin</h5>
           <p>Lorem ipsum dolor uam sequi quia,lorem totam ipsum vero blanditiis accusantium sunt eligendi fugit. 
            Quam inventore ab accusantium aliquid facilis temporibus!</p>
        </figure>
      </div>
      
    </div>

  </section>
  <section id="PicMenu">
     <div class="container my-5 d-flex justify-content-center">
        <div class="col-9 d-flex">
            <figure class="col-7">
                 <img src="../assets/avadaImages/featured_article_2_bg.jpg" alt="">
            </figure>
            <div class="ps-3 d-flex flex-column ">
                <div>
                  <h6 class="fw-bolder">Tutorials & Guides</h6>
                  <hr>
                </div>
                <div class="d-flex p-1">
                    
                    <img class="col-4"  src="../assets/avadaImages/post_feat_img_23-147x118.jpg" alt="">
                    <div class="ms-3">
                        <h6 class="fw-bolder ms-2">Donec ornare pretium eget scelisque justo</h6>
                    <span class="text-secondary calendar">October 11th,2015 | Comment 0</span>
                    </div>
                </div>
                <div class="d-flex p-1">
                    <img class="col-4" src="../assets/avadaImages/post_feat_img_22-147x118.jpg" alt="">
                    <div class="ms-3">
                         <h6 class="fw-bolder">Fusce solicitudin nunc sed placerat varius</h6>
                    <span class="text-secondary calendar">October 11th,2015 | Comment 0</span>
                    </div>
                   
                </div>
                <div class="d-flex p-1">
                    <img class="col-4" src="../assets/avadaImages/post_feat_img_20-147x118.jpg" alt="">
                    <div class="ms-3">
                         <h6 class="fw-bolder">Proin eu purus sed aru aliquet curabir vens</h6>
                        <p class="text-secondary calendar">October 11th,2015 | Comment 0</p>
                    </div>
                </div>
            </div>
          
        </div>
    </div>

  </section>
</div>

</template>
<script>
export default{
    name:'BaseMain',

}
</script>
<style lang="scss" scoped>
@import '../assets/scss/style.scss';
.mw-100{
  max-width:100%;
  max-height:700px;
}
.upside{
  position:absolute;
  
}
.titleBig{
  font-size:150px;
  text-align:left;
}
.bigImage{
  background-color:white;
}
.smallImage{
    flex-basis: 25%;
}
button{
  border:none;
}
.wid-50{
  width:50%;
  
}

figure img{display:inline-block;
width:100%;}
img{
   max-width:100%;
}
.marginNegative{
  margin-top:-10px;
}
  hr{width:20%;text-align: center;color:orangered}
  .w-60{max-width:60%;}
  .imgClose{max-width:100%;text-align:center;}
  .pippo{
    border:1px solid black;
  }
  .letterSpace{
    letter-spacing:4px;
  }
  .calendar{
    font-size:12px;
  }
</style>