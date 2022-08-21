<script setup>

import SidebarMenu from './components/SidebarMenu.vue'
import HeaderH from './components/HorizontalMenu.vue'
</script>

<template>
 
    <header>
      <HeaderH /> 
      <SidebarMenu />
    </header>

  
      

    <main>
      
      <div class="box1" style="background-color: #5006A4"> 
      <div> <h1>  26K   (-12%)</h1></div> 
      <div><p> Conversion </p> </div>
      </div>
      <div class="box1" style="background-color: #286CF4"> 
      <div> <h1> 26K (-12%) </h1></div> 
      <div><p> Conversion </p> </div>
      </div>
      <div class="box1" style="background-color: #FFC300"> 
      <div> <h1> 26K (-12%)</h1> </div> 
      <div><p> Conversion </p> </div>
      </div>
      <div class="box1" style="background-color: #D54829"> 
      <div> <h1> 26K (-12%)</h1> </div> 
      <div><p> Conversion </p> </div></div>

    </main>

    <div>
      <img class="graph" src="./assets/Giga_graph.png"/>
    </div>

    <footer>
        <div class="box2" style="background-color: #2C2F79"> 
          <img class="iconSpe" src="https://cdn.discordapp.com/attachments/1010569005746102274/1010973263725346896/facebook-770688_640.webp"/>

      </div>
      <div class="box2" style="background-color: #0074FE"> 
        <img class="iconSpe" src="https://www.unamur.be/info/images/logo-twitter/image_preview"/>
      </div>
      <div class="box2" style="background-color: #5755EA"> 
        <img class="iconSpe" src="https://cdn.discordapp.com/attachments/1010569005746102274/1010971859711447051/LinkedIn_logo_initials.png"/>
      </div>
      
    </footer>
</template>


<style scoped>

  main {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      grid-template-rows: 1fr;
  }

.graph {
  padding-left: 15%;
}
  .iconSpe {
    width: 20%;
    margin-top: 5%;
  }

  .box1 {
    border-radius: 10px;
   color: white;
    margin: 10%;
    padding-left: 10%;
    padding-top: 5%;
  }
  .box2 {
    border-radius: 5px;
   color: white;
    margin: 8%;
    text-align: center;
    /* padding-left: 10%;
    padding-top: 5%; */
  }

  footer {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: 1fr;
  }
</style>
