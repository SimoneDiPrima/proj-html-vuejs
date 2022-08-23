<template>
<div>
  <div class="lightblue">
    <header class="container">
    <nav class="d-flex justify-content-between align-items-center text-white p-2">
      <img src="./assets/avadaImages/logo.png" alt="">
      <ul class="d-flex align-items-center">
        <li class="me-2">Home</li>
        <li class="me-2">Apple</li>
        <li class="me-2">Microsoft</li>
        <li class="me-2">Android</li>
        <li class="me-2">Forums</li>
        <li class="me-2">Contacts us</li>
        <li>
          <button class="bg-dark text-white p-2">join us</button>
        </li>
      </ul>
    </nav>
   
  </header>

  </div>
 
  <section class="bigImage">
    <img class="mw-100 position-relative" src="./assets/avadaImages/home_slider_bg.jpg" alt="">
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
    <div class="text-warning">
  <hr class="offset-5 col-2">
</div>
  </section>
  
</div>
 
</template>

<script>

export default {
  name: 'App',
  components: {
    
  }
}
</script>

<style lang="scss">
@import './assets/scss/style.scss';
li{
  list-style-type:none;
}
.mw-100{
  width:100%;
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
.lightblue{
  background-color: #27aabe;
}
button{
  border:none;
}
.wid-50{
  width:50%;
  
}
img{display:inline-block}
.marginNegative{
  margin-top:-10px;
}
  hr{width:20%;text-align: center;}
</style>
