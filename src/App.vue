<template>
  <div class="globalContainer">
    <left-container/>
    <div class="topAndTeam">
      <top-container/>
      <team-statistics/>
      <button-container/>
      <table-person/>
      <pagination-table/>
    </div>
  </div>

</template>


<script>
import TopContainer from "@/components/TopContainer.vue";
import LeftContainer from "@/components/LeftContainer.vue";
import TeamStatistics from "@/components/TeamStatistics.vue";
import ButtonContainer from "@/components/ButtonContainer.vue";
import TablePerson from "@/components/TablePerson.vue";
import PaginationTable from "@/components/PaginationTable.vue";
export default {
  components:{
    TopContainer,LeftContainer,
    TeamStatistics,ButtonContainer,TablePerson,PaginationTable
  }
}

</script>

<style>


*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.globalContainer{
  background: #F5F5F5;
  width: 100%;
  display: flex;
}
.topAndTeam{
  display: flex;
  flex-direction: column;
}
</style>
