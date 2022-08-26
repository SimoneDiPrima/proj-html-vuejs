<template>
    <div>
        <footer class="container">
            <div>
                <ul class="mb-1">
                    <h6><strong>{{footerList.title}}</strong></h6>
                    <li  class="mb-1 fw-bolder"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{footerList.firstItem}}</a></li>
                    <li  class="mb-1 fw-bolder"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{footerList.secondItem}}</a></li>
                    <li  class="mb-1 fw-bolder"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{footerList.thirdItem}}</a></li>
                    <li  class="mb-1 fw-bolder"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{footerList.lastItem}}</a></li>
                </ul>
            </div>
        </footer>
        
    </div>
   
</template>
<script>

export default{
    name:'BaseFooter',
     props:{
        footerList:Object,
    },
}


</script>
<style lang="scss" scoped>
@import '../assets/scss/style.scss';
li a{
text-decoration:none;
color:black;
&:hover{
    color:goldenrod;
}
}
    
</style>