<template>
  <div class="about">
    <h1>Om oss och vår startup</h1>
    <div class="aboutIdea">
      <h3>Ideen</h3>
      <p>Skriva lite om iden</p>
    </div>
    <div class="aboutUsGrid">
      <img class="aboutUsImg" alt="glad tjej" src="../assets/gladtjej.jpg">

      <div class="aboutUsTextbox">
        <h3>Tora Svensson Nordin</h3>
        <p>Här berättar vi om tora och hej o hå va hon är bra osv osv. Vi älskar Tora</p>
        <p>Bilden bredvid ska va bild på Tora</p>
      </div>

      <div class="aboutUsTextbox">
        <h3>Lina Melkersson</h3>
        <p>Här berättar vi om Lina</p>
        <p>Bilden bredvid ska va bild på Lina</p>

      </div>

      <img class="aboutUsImg" alt="glad tjej" src="../assets/gladtjej.jpg">
    </div>
  </div>
</template>

<style scoped>

.aboutIdea {
  border-radius: 15px;
  background-color: rgba(255, 255, 255, 0.706);
  justify-content: center;
  width: 70%;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 3vh;
  padding: 2px;
}
.aboutUsGrid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  justify-content: center;
  align-content: center;
  justify-items: center;
  align-items: center;
}

.aboutUsTextbox {
  width: 95%; 
  height: 95%;
  border-radius: 15px;
  background-color: rgba(255, 255, 255, 0.706);
  margin: 5vh;
}



.aboutUsImg {
  display: grid;
  object-fit: cover;
  height: 95%;
  width: 95%;
  border-radius: 15px;
}

</style>
