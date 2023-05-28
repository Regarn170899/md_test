<template>
  <div class="topContainer">
    <div class="burgerContainer" >
      <div class="shadowContainer"></div>
      <img class="burger" src="../assets/Burger.svg" alt="Burger">
      <span>Team</span>
    </div>
    <div class="authorContainer">
      <img src="../assets/search.svg" alt="search">
      <img class="bell" src="../assets/bell.svg" alt="bell">
      <img  class="arrowImg" src="../assets/autor.svg" alt="autor">
      <span class="authorName">Ernest Eberly</span>
      <button class="arrowBtn">
        <img src="../assets/arrow.svg" alt="arrow">
      </button>

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style  scoped>

.topContainer{
  background: white;
  width: 1848px;
  height: 76px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.burgerContainer{
  display: flex;
  align-items: center;
  font-family: 'Commissioner',serif ;
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 150%;

}
.burger{
  margin-right: 28px;
}
.shadowContainer{
  width: 28px;
  height: 76px;
  background: linear-gradient(90deg, rgba(42, 53, 90, 0.04) 0%, rgba(42, 53, 90, 0) 100%);

}
.authorContainer{
  display: flex;
  align-items: center;
}

.authorName{
  font-family: 'Commissioner',serif ;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  margin-right: 12px;
}
.arrowBtn{
  width: 20px;
  height: 20px;
  background: #F5F7FB;
  border-radius: 6px;
  border: 0;
  margin-right: 28px;
}
.arrowImg{
  margin-right: 12px;
  padding-left: 28px;
  border-left: 1px solid #E5E8EF;;
}
.bell{
  margin-right: 28px;
  margin-left: 37.75px;

}

</style>