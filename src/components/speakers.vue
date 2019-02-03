<template>
<div class="speakers">
    <div class="title">
        <h1 style="margin:auto">Speakers</h1>
       
        <div class="hl"></div>
    </div>
    <div class="speaker-container">
        <div class="speaker-cards">
            
            <div class="speaker-content">
                <img src="../assets/speakers/manjesh.jpeg" height="250px" width="250px">
                <h1>Manjesh P Shetty</h1>
                <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            
            <div class="speaker-content" >
                <img src="../assets/speakers/musthu.jpeg" height="250px" width="250px">
                <h1>Musthaq Ahmed</h1>
                <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            
            <div class="speaker-content">
                <img src="../assets/speakers/rumaan.png" height="250px" width="250px">
               <h1>Rumaan Khalander</h1>
               <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
           
            <div class="speaker-content" >
                <img src="../assets/speakers/abhi.png" height="250px" width="250px">
                <h1>Abhishek Gatty</h1>
                <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            
            <div class="speaker-content" >
                <img src="../assets/speakers/chamz.jpg" height="250px" width="250px">
               <h1>Chaman K</h1>
               <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
 name:'speakers'   
}
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400');
.hl{
  position: relative;
    z-index: 1;
    background-color: #f0326b;
    display: inline-block;
    width: 95px;
    height: 5px;
    margin-top: 10px;
    margin-bottom: 10px;
    border-radius: 3px;
    
}

.title{
    margin: auto;
    
    background-color: #292d53;
    color: white;
    font-size: 25px;
    padding-top:5px; 
    text-align: center;
    
    font-family: 'Open Sans',sans-serif;
}

body{
    margin: auto;
}
.speaker-container{
    padding-top:30px; 
    align-content: space-between;
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
    background-color: #292d53;
    margin: auto;
    overflow: hidden;
}
img{
    padding: 10px;
    background-color: white;
    border-radius:140px ;
}
.speaker-cards{
    
    padding: 25px;

    width:500px;
    height: 550px;
   
    font-family: 'Open sans',sans-serif;
    color: white;
    
}
.speaker-cards p{
    color: grey;
    margin: 25px;
    
}
.speaker-content {
    background-color:#2c305e;
    
    
    align-items: center;
    box-shadow: 10px 10px 10px 10px rgba(0.2, 0.2, 0.2, 0.2);
     display: flex;
     flex-direction: column;
     justify-content: space-evenly;
}
</style>
