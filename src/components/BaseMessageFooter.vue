<template>
    <div class="col-3">
      <h3>{{footerMessage.title}}</h3>
      <p>{{footerMessage.item}}</p>
    </div>

</template>
<script>
export default{
    name:'BaseMessageFooter',
    props:{
        footerMessage : Object
    }
}


</script>
<style lang="scss">
@import '../assets/scss/style.scss';

</style>