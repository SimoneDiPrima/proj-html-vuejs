<template>
    <div>
        <footer class="container">
            <ul class="d-flex justify-content-between offset-1 col-9 mt-5">
                <li class="col-3 ms-3"><h6><strong>{{FooterMessage.title}}</strong></h6>
                    <p>{{FooterMessage.item}}
                    </p>
                </li>
               <li v-for="(item,i) in FooterListItems" :key="i" >
                    <ul>
                        <li class="mb-1"><h6><strong>{{item.title}}</strong></h6></li>
                        <li  class="mb-1"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{item.firstItem}}</a></li>
                        <li  class="mb-1"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{item.secondItem}}</a></li>
                        <li  class="mb-1"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{item.thirdItem}}</a></li>
                        <li  class="mb-1"><a href="#"><strong><i class="fa-solid fa-chevron-right"></i></strong> {{item.lastItem}}</a></li>
                    </ul>
                </li>
            </ul>
        </footer>
    </div>
</template>
<script>
export default{
    name:'BaseFooter',
    data(){
        return{
            FooterMessage:{
                title:'TECH FORUM',
                item:'sed semper, nisi id feugiat eleifend,erat est digissim fetis,quis auctor elit enim nec ante, cras et nibh risus,Pelientesque non mi sit amet mi intermentum'
            },
            FooterListItems:[
                {title:'POPULAR TOPICS',
                firstItem:'Nam a dolor voluptat massa autor semper',
                secondItem:'Sed euismod nunc urna fermentum arcu dapibus fringilla',
                thirdItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                lastItem:'Curabitur a scellerisque ligula'
                },
                {title:'RECENT TOPICS',
                firstItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                secondItem:'Proin at ligula saggittis vestibulum nisi vitae',
                thirdItem:'Sed nec metus at est tincidunt elementum',
                lastItem:'Nulla egestas nulla eu nulla suscipit molestie'
                },
                {title:'LATEST REPLIES',
                firstItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                secondItem:'Cras Lacinia tellus id mauris finibus lacus molestie',
                thirdItem:'Nulla egestas nulla eu nulla suscipit molestie',
                lastItem:'Mauris ac nibh quis eros saggittis lacinia a et dui'
                },
                ]
        }
    }
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