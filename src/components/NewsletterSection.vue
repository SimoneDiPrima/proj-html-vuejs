<template>
<!-- sezione newsletter formata da titolo input e button collegato al form -->
    <div class="bgGray pb-5">
        <h1 class="text-center p-5">Subscribe to our Newsletter</h1>
        <form action="#" method="GET" class="text-center">
            <input size="60" type="text" placeholder="insert your email*" class="bg-light me-2 p-2">
            <button class="blackButton p-2">SEND</button>
        </form>
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
    background-color:$silver_Caliche;
}
.blackButton{
    background-color:$Shark;
    color:$color_White;
    width:150px;
}
</style>