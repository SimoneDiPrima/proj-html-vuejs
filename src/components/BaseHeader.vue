<template>
<div class="lightblue">
    <header class="container">
    <nav class="d-flex justify-content-between align-items-center text-white p-2">
      <img src="../assets/avadaImages/logo.png" alt="">
      <ul class="d-flex align-items-center">
        <li class="me-2">{{ listItemFirst }}</li>
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
</template>
<script>
export default{
    name:'BaseHeader',
    props:{
        listItemFirst : String,
    }

}
</script>
<style lang="scss">
@import '../assets/scss/style.scss';
li{
  list-style-type:none;
}
.lightblue{
  background-color: #27aabe;
}
</style>