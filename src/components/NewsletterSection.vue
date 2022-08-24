<template>
    <div class="bgGray pb-5">
       <h1 class="text-center p-5">Subscribe to our Newsletter</h1>
       <div class="text-center">
        <input size="60" type="text" placeholder="insert your email*" class="bg-light me-2 p-2">
        <button class="blackButton p-2">SEND</button>
       </div>
    </div>

</template>
<script>
export default{
    name:'NewsletterSection',
}

</script>
<style lang="scss" scoped>
@import '../assets/scss/style.scss';
.bgGray{
    background-color: #aeaeae;
}
.blackButton{
    background-color: #1a1b1b;
    color:white;
    width:150px;
}

    
</style>