<template>
<div class="footer">
    <div class="social">
        <a href="https://github.com/so-sc">GitHub</a>
        <a href="https://instagram.com/sosc.sahyadri">Instagram</a>
        <a href="https://linkedin.com/company/sosc-sahyadri">LinkedIn</a>
    </div>
    <div class="address">
        <p>
        <strong>Sahyadri Open-Source Community</strong>
        <br>
        Sahyadri College of Engineering and Management, Adyar, Mangalore - 575007 IN
        <br>
        <br>
        sosc@sahyadri.edu.in
        </p>
    
    </div>
    <div class="Copyright">SOSC &copy 2019</div>
</div>
</template>

<style scoped>
     @import url('https://fonts.googleapis.com/css?family=Open+Sans:400');
     
     .social{
        display:flex;
        background-color:#292d53; 
        color: white;
        font-size: 15px;
        font-family: 'Open Sans',sans-serif;
        
     }
     .address{
         display: flex;
         background-color: #292d53;
         color: white;
        font-size: 15px;
        font-family: 'Open Sans',sans-serif;
     }
     .Copyright{
         
         text-align:center;
         background-color: #292d53;
         color: white;
          font-size: 15px;
          font-family: 'Open Sans',sans-serif;
     }
     a{
        text-decoration: none;
        padding: 10px;
        color: white
     }
</style>

<script>
export default {
    name:'footer'
}
</script>

