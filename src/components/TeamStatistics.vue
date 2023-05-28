<template>
  <div class="container">
    <img class="iconTeam" src="../assets/Teamstatistics/iconTeam.svg" alt="icon">
    <span class="teamText">Team</span>
    <img class="infoImg" src="../assets/Teamstatistics/Info.svg" alt="Info">
    <div class="numberC1">
      <span class="numberText">130</span>
      <span class="description">members</span>
    </div>
    <img src="../assets/Teamstatistics/Line.svg" alt="Line">
    <div class="numberC2">
      <div>
        <span class="numberText">36</span>
        <img class="ellipse" src="../assets/Teamstatistics/Ellipse.svg" alt="Ellipse">
      </div>
      <span class="description">online</span>
    </div>
    <img src="../assets/Teamstatistics/Line.svg" alt="Line">
    <div class="numberC3">
      <span class="numberText">50</span>
      <span class="description">men</span>
    </div>
    <div class="numberC4">
      <span class="numberText">80</span>
      <span class="description">women</span>
    </div>
    <img src="../assets/Teamstatistics/Line.svg" alt="Line">
    <div class="numberC4">
      <span class="numberText">29</span>
      <span class="description">average age</span>
    </div>
    <img src="../assets/Teamstatistics/Line.svg" alt="Line">
    <div class="numberC4">
      <span class="numberText">265</span>
      <span class="description">days work on average</span>
    </div>
    <img src="../assets/Teamstatistics/Line.svg" alt="Line">
    <div class="numberC4">
      <span class="numberText">36</span>
      <span class="description">days work newest employee</span>
    </div>
    <img src="../assets/Teamstatistics/Line.svg" alt="Line">
    <div class="numberC4">
      <span class="numberText">1256</span>
      <span class="description">days work oldest employee</span>
    </div>
  </div>
</template>
<script>
export default {

}
</script>

<style  scoped>
.iconTeam{
  margin-left: 28px;
}
.container{
  align-items: center;
  margin-top: 28px;
  margin-left: 28px;
  border-radius: 12px;
  display: flex;

  width: 1403px;
  height: 79px;
  background: white;
}
.teamText{
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  margin-left: 16px;
}
.infoImg{
  margin-left: 4px;
  margin-bottom: 4px;
}
.numberText{
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 130%;
  color: #2A355A;
}
.description{
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 150%;
  color: #8591AE;
}
.numberC1{
  display: flex;
  flex-direction: column;
  margin-left: 72px;
  margin-right: 36px;
}
.numberC2{
  margin-left: 36px;
  margin-right: 41px;

}
.ellipse{
  margin-left: 5px;
  margin-bottom: 12px;
}
.numberC3{
  display: flex;
  flex-direction: column;
  margin-left: 36px;
}
.numberC4{
  display: flex;
  flex-direction: column;
  margin-left: 36px;
  margin-right: 36px;
}


</style>