<template>
<div>
<HEADER_VUE/>
  <router-view/>
</div>
</template>


<script>

import HEADER_VUE from '@/components/Header.vue'
export default {
    components:{
      HEADER_VUE,
   
    }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
html,body{
  margin: 0%;
  padding: 0px;
}

</style>
