<template>
    <div class="nav">
<div class="logo_container">
    <div class="logo">
        <h1 id="logo">MAD HATTERS</h1>
    </div>
</div>

<div :class = "{dd:dd}" class="nav_menu">
    <div class="content">
        <ul>
            <li :class="{li:li}">For_men</li>
            <li :class="{li:li}">For_women</li>
            <li :class="{li:li}">For_any-one</li>
            <li :class="{li:li}">For_no-one</li>
        </ul>
    </div>
</div>
<Face/>

<Body_Content/>
    </div>
</template>

<script>
import Body_Content from './Body'
import Face from './FaceHeader'
export default {
    data(){
        return{
            dd:false,
            li:false
        }
    },
    components:{
        Face,Body_Content
    },
    computed:{

    },
    created(){
    //   window.addEventListener('scroll',()=>{

    //       this.dd=true
    //       this.li=true
          
    //   })
    },
    destroy(){

    },
    methods:{

    }
}
</script>

<style scoped>
.li{
    color: #fff;
}
.dd{
    border-bottom: 1px solid #000;
    margin-bottom: 0px;
    padding-bottom: 0px;
    background: rgba(15, 13, 13, 0.568);
    align-items:center;
    color: rgb(90, 11, 11);
}
@media screen and (max-width:590px){
    ul li{
        margin:0 10px;
    }
}
ul li{
    word-wrap: none;
}
#logo{
    color: #000000;

}
.logo_container{
    margin: 0%;
    padding: 0px;
}
ul{
    display: flex;
    justify-content: space-around;
}
li{
    list-style: none;
    height: 32px;
    margin: 0 32px;
    color: #23242C;
    transition:all 3s ease;
}

li:hover{
    border-bottom: 1px solid #000;
}
.nav_menu{
    width: 100%;
    display: flex;
    justify-content: space-around;
    margin: 0%;
    padding: 0px;
    height: 14vh;
    top:0;

    z-index: 101;
    transition: all 2s ease;
}
.nav_menu content{
    width: 70%;
}
</style>
