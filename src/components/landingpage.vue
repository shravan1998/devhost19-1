<template>
    <div class="ld">
    <div class="bg">
        <div class="content">
        <h1>Student developers meet</h1>
        <h1>2019</h1>
        <p >
            Join us this march to celebrate our
            <br>
            annual students developers meet by sosc
            </p>
        </div>
    </div>
        
       
    </div>
</template>
<script>
export default {
    name:'landing page',
    
    
}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:800');

body{
    margin: auto;
}
.ld{
    margin: auto;
}
h1{
    
    margin: auto;
}
.bg{
    height: 600px;
    width:100%;
    z-index: -1;
    background-image: url('../assets/bg.jpg');
    background-repeat: no-repeat;
    background-size: 100%;
     -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
    margin: 0;
    padding: 0;
}
.content{
    padding-top:220px; 
    color: white;
    font-size:30px; 
    font-family: 'Open Sans', sans-serif;
    text-align:center;
  
}
.content p{
    text-align: center;
   align-content: center;
   
    font-size: 25px;
   
}
@media(max-width:900px){
  
  .content{font-size: 20px}
  .content p{font-size:17px; }
  
  
}
@media(min-width:568px){
}

</style>
