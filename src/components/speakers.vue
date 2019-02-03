<template>
<div class="speakers">
    <div class="title">
        <h1 style="margin:auto">Speakers</h1>
       
        <div class="hl"></div>
    </div>
    <div class="speaker-container">
        <div class="speaker-cards">
            <img src="../assets/speakers/manjesh.jpeg">
            <div class="speaker-content">
                <h1>Manjesh P Shetty</h1>
                <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            <img src="../assets/speakers/musthu.jpeg" style="order:2">
            <div class="speaker-content" style="text-align:right; padding-right:40px;">
                <h1>Musthaq Ahmed</h1>
                <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            <img src="../assets/speakers/rumaan.png">
            <div class="speaker-content">
               <h1>Rumaan Khalander</h1>
               <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            <img src="../assets/speakers/abhi.png" style="order:2">
            <div class="speaker-content" style="text-align:right; padding-right:40px;">
                <h1>Abhishek Gatty</h1>
                <div class="hl"></div>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
            </div>
        </div>
        <div class="speaker-cards">
            <img src="../assets/speakers/chamz.jpg">
            <div class="speaker-content" >
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
img{
    height:400px;
    width: 400px;
    
}
body{
    margin: auto;
}
.speaker-container{
    padding-top:30px; 
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    background-color: #292d53;
    margin: auto;
}
.speaker-cards{
    display: flex;
    padding-top:10px; 
    justify-content: space-evenly;
    font-family: 'Open sans',sans-serif;
    color: white;
    
}
.speaker-cards p{
    color: grey;
}
.speaker-content {
    padding-left: 60px;
    text-align: left;
   
    display: flex;
     flex-direction: column;
}
</style>
