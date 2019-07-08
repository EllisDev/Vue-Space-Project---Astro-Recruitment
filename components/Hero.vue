<template>
<div class="main-container">
      <div 

      v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: -3
                  }"
      
      
      class="space-man-holder"></div>

      <div class="heroholder">
            <div 
            v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: -5
                  }"
            class="hero-content">

                  <h1>Thinking Bigger Than Ever Before, Today.</h1>
                  <p>Sometimes looking for great talent can feel out of this world. But we connect businesses just like yours to some of the greatest creatives in the world. Whether you are looking for someone part-time or full time we’ve got the creatives your business deserves. </p>

                  

                  <a href="#"><div class="btn">Find a Job</div></a>
            </div>
            
      </div>

      <div
       
              v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: -2
                  }"
            
            
      
       class="side-items">
            <p class="sidepanel">SPACE SEQUENCE &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp VOLUME #1240</p>
            </div>
      <p class="scrolldown"><img src="../assets/img/scroll-down.png"></p>
</div>

</template>


<script>   

</script>


<style scoped>


.space-man-holder {
      background-image: url(../assets/img/space-man.png);
      background-repeat: no-repeat;
      height: 610px;
      position: absolute;
      z-index: 999;
      width: 40%;
      right: 0;
      bottom: 10%;
}

.btn {
      border: 1px solid #fff;
      color: #fff;
      max-width: 120px;
      text-align: center;
      padding: 10px;
      margin-top: 30px;
      font-size: 0.813em;
      transition: 0.5s;
      box-shadow: 8px 8px 0 0 #fff;
}

.btn:hover {
      background-color: #fff;
      transition: 0.5s;
      color: #5B409B;
      transform: translate3d(0px, 3px, 0px);
      box-shadow: rgb(255, 255, 255) 0.5px 0.5px 0px 0px;
      border-color: rgb(255, 255, 255);
      transition: all 0.3s ease 0s;
}

.main-container {
}

.scrolldown {
      width: 30px;
      position: absolute;
      bottom: 0;
      left: 50%;
      padding-bottom: 20px;
}

.heroholder {
      background-image: url(../assets/img/space-bg.png);
      height: 100vh;
      background-size: cover;
      background-position: right;
      display: flex;
      align-items: center;
}

.sidepanel {
  
      transform: rotate(270deg);
      font-size: 0.625em;
}

.side-items {
    position: absolute;
      bottom: 50%;
}

.hero-content {
      margin: 0 30px;
      margin-left: 160px;
      max-width: 40%;

}

h1 {
      font-size: 2.5em;

      color: #fff;
      font-family: 'Nunito', sans-serif;
      font-weight: 700;
      margin-bottom: 20px;
}

p {
      font-size: 1em;
      font-family: 'Nunito', sans-serif;
      font-weight: 300;
      color: #fff;
}

@media (max-width:650px) {
      .hero-content {
            margin: 0 auto;
            max-width: 61%;
      }
}

@media (max-width: 500px) {

      h1 {
            text-align: center;
            font-size: 2em;
      }

      p {
            text-align: center;
            font-size: 0.8em;
      }

      .btn {
            margin: 0 auto;
            margin-top: 30px;
      }

      .hero-content {
      
      }

      .heroholder {
            background-image: url(../assets/img/mobile-hero-bg.png);
      }

      .sidepanel {
            left: -140px;
      }
}

</style>
