<template>
<div class="speakers">
    <div class="title">
        <h1 style="margin:auto">The Schedule</h1>
       
        <div class="dash"></div>
        <div class="schedule-cards" style=" background:#292d53; color: grey; font-size: 20px;"><p>what follows, is the schedule for the Events</p></div>
    </div>
    <div class="schedule-container">
            <ul class="days">
                <li id="day1" class="day1"><button  class="day-button-1"  id="bt1" @click="changescheduleday1"  >Day 1</button></li>
                <li id="day2" class="day2" style="background-color:#292d53;"><button   id="bt2" class="day-button-2"   @click="changescheduleday2" style="background-color:#292d53;color:grey;"  >Day 2</button></li>
                <br />
            </ul>
        
        <div id="sc1" class="schedule-1">        
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">day 1</p>
                    <p style="text-align: center;">8:00 AM to 9:00 AM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">First Event</p>
                    <p style="text-align: center;">9:00 AM to 10:00 AM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Second Event</p>
                    <p style="text-align: center;">10:00 AM to 12:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Third Event</p>
                    <p style="text-align: center;">12:00 PM to 1:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Lunch</p>
                    <p style="text-align: center;">1:00 PM to 2:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Fourth Event</p>
                    <p style="text-align: center;">2:00 PM to 5:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
        </div>
        <div id="sc2" class="schedule-2" style="display:none">        
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">day 2</p>
                    <p style="text-align: center;">8:00 AM to 9:00 AM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">First Event</p>
                    <p style="text-align: center;">9:00 AM to 10:00 AM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Second Event</p>
                    <p style="text-align: center;">10:00 AM to 12:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Third Event</p>
                    <p style="text-align: center;">12:00 PM to 1:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Lunch</p>
                    <p style="text-align: center;">1:00 PM to 2:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
            <div class="schedule-cards">
                <div class="schedule-content">
                    <p style="text-align: center;">Fourth Event</p>
                    <p style="text-align: center;">2:00 PM to 5:00 PM</p>
                    <p>
                        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Recusandae soluta minima earum, veniam excepturi error, culpa unde sed, ea sunt iusto autem neque repudiandae sequi libero ab. Repellendus, repellat officia.
                    </p>
                </div>
            </div>
            <br />
        </div>
    </div>


    
</div>
</template>

<script>
export default {
 name:'schedule',
 methods:{
     changescheduleday2(){
         document.getElementById("sc1").style.display='none';
         document.getElementById("sc2").style.display='block';
         document.getElementById("day2").style.backgroundColor='#222646';
         document.getElementById("bt2").style.backgroundColor='#222646';
         document.getElementById("bt2").style.color='white';
         document.getElementById("day1").style.backgroundColor='#292d53';
         document.getElementById("bt1").style.backgroundColor='#292d53';
         document.getElementById("bt1").style.color='grey';
     },
     changescheduleday1(){
         document.getElementById("sc1").style.display='block';
         document.getElementById("sc2").style.display='none';
         document.getElementById("day1").style.backgroundColor='#222646';
         document.getElementById("bt1").style.backgroundColor='#222646';
         document.getElementById("bt1").style.color='white';
         document.getElementById("day2").style.backgroundColor='#292d53';
         document.getElementById("bt2").style.backgroundColor='#292d53';
         document.getElementById("bt2").style.color='grey';
     }
 }  
}
</script>


<style scoped>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400');
.dash{
  position: relative;
    z-index: 1;
    background-color: #f0326b;
    display: inline-block;
    width: 95px;
    height: 5px;
    margin-top: 10px;
    margin-bottom: 10px;
}

.day-button-1{
    background-color:#222646;
    width: 100%;
    text-decoration: none;
    margin: auto;
    font-size:18px; 
    color: white;
    border: none;
}
.day-button-2{
    background-color:#222646;
    width: 100%;
    text-decoration: none;
    margin: auto;
    font-size:18px; 
    color: white;
    border: none;
}
button:focus {
    outline:0;
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
.schedule-container{
    padding-top:30px;
    flex-direction: column;
    justify-content: space-evenly;
    background-color: #292d53;
    margin: auto;
}
.days{
    
    font-family: 'Open Sans',sans-serif;
    width: 70%;
    display: flex;
    margin: auto;
    color: white;
    background-color: #292d53;
    font-size: 15px;
}

li{ 
    display: inline;
    background-color:#222646;
    border-radius: 10px 10px 0px 0px; 
    padding: 20px 30px;
    
}

.schedule-cards{
    padding: 8px 0px; 
    border-radius: 10px 10px;
    justify-content: space-evenly;
    font-family: 'Open sans',sans-serif;
    color: white;
    background: #222646;
    width: 70%;
    margin: auto;
        display: flex;
     flex-direction: column;
    
}
.schedule-cards p{
    color: grey;
}
.schedule-content {
    font-size: 12px;
    padding: 0px 50px;
    text-align: left;
}
</style>
