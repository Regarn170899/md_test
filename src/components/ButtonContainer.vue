<template>
  <button class="buttonContainer">
    <div class="plus">
      <img   src="../assets/Button/Plus.svg" alt="Plus">
    </div>
    <p class="textBtn">Add new Employee</p>
  </button>
</template>

<script>
export default {

}
</script>

<style scoped>
.plus{
  width: 20px;
  height: 20px;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 6px;
}
.textBtn{
  padding-left: 12px;
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  color: #FFFFFF;
}
.buttonContainer{
  margin-top: 28px;
  margin-left: 28px;
  border: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 184px;
  height: 48px;
  background: #8F20EF;
  border-radius: 12px;
}

</style>