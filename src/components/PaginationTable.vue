<template>
  <div class="paginateContainer">
    <button class="btnArrow1">
      <img class="arrowL" src="../assets/arrowLeft.svg" alt="arrowLeft">
    </button>
    <div class="numberContainer">
      <span class="pageContainer">1</span>
    </div>
    <div class="numberContainer">
      <span class="pageContainer">2</span>
    </div>
    <div class="numberContainer">
      <span class="pageContainer">3</span>
    </div>
    <div class="numberContainer">
      <span class="pageContainer">...</span>
    </div>
    <div class="numberContainer">
      <span class="pageContainer">12</span>
    </div>
    <button class="btnArrow2">
      <img class="arrowR" src="../assets/arrowLeft.svg" alt="arrowR">
    </button>
  </div>
</template>

<script>

export default {

}
</script>

<style scoped>
.paginateContainer{
  margin-top: 28px ;
  margin-left: 28px;
  display: flex;
  width: 1792px;
  height: 68px;
  background: #FFFFFF;
  border-radius: 12px;
  align-items: center;


}
.btnArrow1{
  margin-left: 16px;
  width: 20px;
  height: 20px;
  border: 0;
  background: #F5F7FB;
  border-radius: 6px;
}
.btnArrow2{
  width: 20px;
  height: 20px;
  border: 0;
  background: #F5F7FB;
  border-radius: 6px;
}
.arrowR{
  transform: rotate(180deg);
}
.pageContainer{
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  color: #8591AE;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 36px;
  height: 36px;
  background: #FFFFFF;
  border-radius: 12px;
}
.pageContainer:hover{
  background: #F5F7FB;
  color: #2A355A;
}
</style>