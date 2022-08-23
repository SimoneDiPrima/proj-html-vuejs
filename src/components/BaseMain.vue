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
    <h6>AVADA FORUM IS THE PLACE TO BE</h6>
    <p class="offset-3 col-6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta nulla sunt unde eum excepturi odio perspiciatis ore sed sit, ipsum a nesciunt? Deserunt.Soluta nulla sunt unde eum excepturi odio perspiciatis ore sed sit, ipsum a nesciunt?</p>
  </section>
  <section class="marginNegative text-center mt-5 bg-light">
    <h6>PHASELLUS EGET METUS</h6>
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
</div>

</template>
<script>
export default{
    name:'BaseMain',

}
</script>
<style lang="scss">
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
button{
  border:none;
}
.wid-50{
  width:50%;
  
}
.overText{
  position:absolute;
  top:20%;
  left:15%;
}
figure img{display:inline-block;
width:100%;}
.marginNegative{
  margin-top:-10px;
}
  hr{width:20%;text-align: center;}
  .w-80{max-width:60%;}
</style>