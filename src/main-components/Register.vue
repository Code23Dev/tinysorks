<template>
<div id="wrapper">
  <div>
   <div class="container">
    <div class="col-6">
       <div class="main-input-background">
         <h1 class="main-input-background-title">{{title}}</h1>ss
       </div>
    </div>
    <div class="col-6"></div>
   </div>
  </div>
</div>
</template>

<script>
export default {
  data(){
      return{
           title:"Hesabınıza daxil olun"
      }
  }
  }
</script>

<style  scoped>


#wrapper{
   
    width: 650px  ;
    height: auto;
    background-color: rgb(198, 241, 200);
    margin: 0 auto;
    margin-top: 200px;
    border-radius: 10px;
}
html, 
body {
    margin: 0;
    padding: 0;
    background-color:rgb(250, 28, 65) !important;
}
.main-input-background{
    background: #FFFFFF;
    border-radius: 31px;
}
.main-input-background-title{
    text-align: center;
    color: #000000;
    font-weight: 600;
    font-size: 20px;
    line-height: 44px;
}
</style>
