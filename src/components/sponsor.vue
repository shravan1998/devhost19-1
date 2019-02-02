<template>
    <div class="sponsors">
        <div class="title">
        <h1>Sponsors</h1>
        </div>
        <div class="content">
        <p>Contact us  if you would like to sponsor us</p>
        </div>
    </div>
</template>
<script>
export default {
    name:'sponsor'
}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css?family=Open+Sans:400');
    .title{
    margin: 0;
    background-color: #292d53;
    color: white;
    font-size: 25px;
    padding-top:50px; 
    padding-bottom:10px; 
    text-align: center;
    font-family: 'Open Sans',sans-serif;
    }
    .content{
    margin: auto;

    height: 200px;
    background-color:  #292d53;
    color: grey;
    font-size: 15px;
  
  
    display: flex;
    justify-content: space-evenly;
    overflow-x: hidden;
    font-family: 'Open Sans',sans-serif;
    }
    .content p{
        text-align: center;
        width: 500px;
    }
</style>
