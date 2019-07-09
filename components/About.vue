<template>
<div class="main-container">
    <div class="star">
        <div class="content-container">
        <div class="content-holder">
            <h1>Thinking Bigger Than Ever Before, Today.</h1>
                <p>Sometimes looking for great talent can feel out of this world. But we connect businesses just like yours to some of the greatest creatives in the world. Whether you are looking for someone part-time or full time we’ve got the creatives your business deserves. </p>

        </div>
    </div>

    </div>
    <div 
    v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: 3
                  }"
    
    class="extra-stars"></div>
    <div 
    v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: -3
                  }"
    
    class="extra-stars2"></div>
    
        <div
        
       
              v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: -5
                  }"
         class="left-star"></div>

         <div 
          v-rellax="{
                        // Rellax Options
                        // See: https://github.com/dixonandmoe/rellax#features
                        speed: 5
                  }"
         class="right-star"></div>
</div>
      
</template>


<script>   

</script>


<style scoped>
.extra-stars {

     background-image: url(../assets/img/stars.png);
    width: 100%;
    height: 120%;
    position: absolute;
    top: -130px;
    z-index: 50;
    background-size: cover;
}
.extra-stars2 {

     background-image: url(../assets/img/stars.png);
    width: 100%;
    height: 120%;
    position: absolute;
    top: -70px;
    z-index: 50;
    left: 120px;
    background-size: cover;
}

.main-container {
    background-color: #141830;
    height: 100vh;
    position: relative;
    z-index: 10;
    overflow: hidden;
 
}

.left-star {
    background-image: url(../assets/img/red-star.png);
    width: 40%;
    height: 120%;
    position: absolute;
    top: -400px;
    z-index: -5;
    background-repeat: no-repeat;
}
.right-star {
    background-image: url(../assets/img/blue-star.png);
    width: 40%;
    height: 120%;
    position: absolute;
    top: 350px;
    right: -50px;
    z-index: -5;
    background-repeat: no-repeat;
}


.star {
    background-image: url(../assets/img/stars.png);
    width: 100%;
    height: 100vh;
          display: flex;
    -webkit-box-align: center;
    align-items: center;
    background-size: cover;
 
}

.content-container {
    max-width: 680px;
    margin: 0 auto;
    text-align: center;
    
}

.content-holder {
    padding: 40px;
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
</style>
