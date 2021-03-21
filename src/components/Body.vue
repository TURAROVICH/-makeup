<template>
    <div class="body">
        <div class="content_body">
            <div class="logo"><h2>Brands</h2></div>
            <div class="content">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas vestibulum.
            </div>
        </div>

        <div class="content_body">
            <div class="logo"><h2>Styles</h2></div>
            <div class="content">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas vestibulum.
            </div>
        </div>

        <div class="content_body">
            <div class="logo"><h2>Colors</h2></div>
            <div class="content">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas vestibulum.h
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.body{
    display: flex;
    margin: 100px auto;
    justify-content: space-around;
}
.logo{
    /* H2 */
margin-left: -140px;
font-family: Playfair Display;
font-style: italic;
font-weight: normal;
font-size: 38px;
line-height: 51px;
/* identical to box height */

text-align: center;

color: #111111;
}
.content{
    /* Body Copy */

font-family: Poppins;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 165.9%;
/* or 27px */


color: #9D8888;
height: 109px;
width: 233px;
}

@media screen and (max-width:907px){
    .body{
        flex-direction: column;
    }
    .content{
        margin: 0 auto;
    }
    .logo{
        margin:0 auto;
    }
}
</style>