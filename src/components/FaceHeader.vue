<template>
    <div class="face">
<div>
       <div class="large_text">
                  <div class="helper_text">
           <h6 id="helper_text">introducing</h6>
       </div>
           <div class="text">
               <h1>Mad hetters,</h1>
               <h1>style matters</h1>
           </div>
           <div class="button">
               <button class="btn">Learn more</button>
           </div>
       </div>
</div>

       <div class="logo_img">
           <div class="imgs">
               <img id="img1" src="../assets/logo1.png" alt="">
               <img id="img2" src="../assets/logo2.png" alt="">
           </div>
       </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.btn:hover{
    transform: translate(0,-10px);
    font-size: 20px;
}
.face{
    display: flex;
}
.btn:active{
    border: pink;
    background:transparent;
}
.btn{
    font-family: Poppins;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 24px;

    color: #967675;
    background: #FFFFFF;
    border: 1px solid #CFADAC;
    box-sizing: border-box;
    border-radius: 6px;
    width: 185px;
    height: 61px;
    transition: all 2s ease;
}
#helper_text{
    margin: 0 auto;
    margin-left: -80%;
    color:#967675;
}
.face{
    display: flex;
    justify-content: space-around;
}
.text h1{
    /* H1 */

font-family: Playfair Display;
font-style: normal;
font-weight: bold;
font-size: 80px;
line-height: 110px;
color: #23242C;
}
.text h1{
    margin: 0cm;
    padding: 0em;
}
#img1{
    z-index: 100;
    margin-left: -155px;
    position: absolute;
    margin-top:0;
}
#img2{
    z-index: 99;
    position:none;
    padding-top: 120px;
}

@media screen and (max-width:970px) {
    .text h1{
    font-size: 60px;
    line-height: 80px;
    }
    #helper_text{
margin-left: 70%;
    }
}

@media screen and (max-width:864px) {
        #helper_text{
margin-left: 60%;
    }
    .imgs{
        display: flex;
        flex-direction: column;  
        box-sizing: border-box;
        background-size: cover;
  }
    .face{
        flex-direction: column;
    }
    #img1{
        margin:20px auto;
        position: relative;
    }
    #img2{
        padding-top: 0px;
        box-sizing: border-box;
        width: 256px;
        height: 370px;
        margin: 0 auto;
    }
}
</style>