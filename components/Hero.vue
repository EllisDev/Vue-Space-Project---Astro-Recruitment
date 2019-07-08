<template>
<div class="main-container">

      <div class="heroholder">

            <div class="hero-content">

                  <h1>Thinking Bigger Than Ever Before, Today.</h1>
                  <p>Sometimes looking for great talent can feel out of this world. But we connect businesses just like yours to some of the greatest creatives in the world. Whether you are looking for someone part-time or full time we’ve got the creatives your business deserves. </p>

                  <p class="sidepanel">SPACE SEQUENCE &nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp VOLUME #1240</p>

                  <p class="scrolldown"><img src="../assets/img/scroll-down.png"></p>

                  <a href="#"><div class="btn">Find a Job</div></a>
            </div>
      </div>
     
</div>

</template>


<script>   

</script>


<style scoped>

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
      background-image: url(../assets/img/background.png);
      height: 100vh;
      background-size: cover;
      background-position: right;
      display: flex;
      align-items: center;
}

.sidepanel {
      position: absolute;
      bottom: 50%;
      transform: rotate(270deg);
      left: -10px;
      font-size: 0.625em;
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
            left: -61px;
      }
}

</style>
