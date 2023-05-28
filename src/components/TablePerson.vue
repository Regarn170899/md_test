<template>
  <div class="tableContainer">
  <table>
    <thead class="tableHeader">
    <tr class="headerColum">
      <th class="th1 thR1">
        <div class="thContainer" >
          <img src="../assets/Table/SearchTable.svg" alt="Search">
          <span class="nameTh">Business Name</span>
          <img src="../assets/Table/Arrow.svg" alt="arrows">
        </div>
      </th>
      <th class="th1">
        <div class="thContainer" >
          <img src="../assets/Table/CloseTable.svg" alt="Close">
          <span>Team</span>
          <img src="../assets/Table/Arrowblack.svg" alt="arrows">
          <div class="arrowContainer">
            <img src="../assets/arrow.svg" alt="arrow">
          </div>
        </div>
      </th>
      <th class="th1">
        <div class="thContainer" >
          <img src="../assets/Table/CloseTable.svg" alt="Close">
          <span>Role</span>
          <img src="../assets/Table/Arrow.svg" alt="arrows">
          <div class="arrowContainer">
            <img src="../assets/arrow.svg" alt="arrow">
          </div>
        </div>
      </th>
      <th class="th1">
        <div class="thContainer" >
          <img src="../assets/Table/SearchTable.svg" alt="Search">
          <span class="nameTh">Gmail</span>
          <img src="../assets/Table/Arrow.svg" alt="arrows">
        </div>
      </th>
      <th class="th1">
        <div class="thContainer" >
          <img src="../assets/Table/CloseTable.svg" alt="Close">
          <span>Birthday</span>
          <img src="../assets/Table/Arrow.svg" alt="arrows">
          <div class="arrowContainer">
            <img src="../assets/arrow.svg" alt="arrow">
          </div>
        </div>
      </th>
      <th class="th1">
        <div class="thContainer" >
          <span>Telegram</span>
          <img src="../assets/Table/Arrow.svg" alt="arrows">
        </div>
      </th>
      <th class="th1">
        <div class="thContainer" >
          <span>Last Login</span>
          <img src="../assets/Table/Arrow.svg" alt="arrows">
        </div>
      </th>
      <th class="th1 thR2">
        <div class="thContainer" >
          <span>User permissions</span>
        </div>
      </th>
    </tr>
    </thead>
    <tbody>
    <tr  class="rowInfo"  v-for="row in rows" :key="row.id">
      <td key={{row.id}}>
        <div class="ferstItem">
          <img :src="row.src" alt="author">
          <span class="nameTD"> {{row.name}}</span>
        </div>
      </td>
      <td> {{row.team}}</td>
      <td>{{row.role}}</td>
      <td>{{row.mail}}</td>
      <td>{{row.birthday}}</td>
      <td>{{row.tg}}</td>
      <td>{{row.lastLogin}}</td>
      <td class="userPermissionsContainer">
        <button class="btnEdit">
          <img src="../assets/Table/pencil.svg" alt="pencil">
          <span class="textEditBtn">Edit</span>
        </button>
        <img class="trash" src="../assets/Table/trash.svg" alt="trash">
      </td>
    </tr>
    </tbody>
  </table>
  </div>


</template>

<script>
export default {
  data() {
    return {
      rows: [
        {
          id: 1,
          src: require("../assets/Table/a1.svg") ,
          name: "Sarah Connor",
          team: "Crosty",
          role: 'Team Lead',
          mail: 'sarahconnor@gmail.com',
          birthday: "25.04.1994",
          tg: "@sarahconnor",
          lastLogin: "03.11.2021"
        },{
          id: 2,
          src: require("../assets/Table/NoAvatar1.svg") ,
          name: "Arnold Brown",
          team: "Gunters",
          role: 'Seo Specialist',
          mail: 'arnoldbrown@gmail.com',
          birthday: "12.04.1989",
          tg: "@arnoldbrown",
          lastLogin: "02.11.2021"
        },
        {
          id: 3,
          src: require("../assets/Table/a2.svg") ,
          name: "Ernest Eberly",
          team: "Flamethrower",
          role: 'Semantic Specialist',
          mail: 'ernesteberly@gmail.com',
          birthday: "17.06.1993",
          tg: "@ErnestEberly",
          lastLogin: "03.11.2021"
        },{
          id: 4,
          src: require("../assets/Table/a3.svg") ,
          name: "Lance Thomas",
          team: "Wizards",
          role: 'Seo Specialist',
          mail: 'lancethomas@gmail.com',
          birthday: "12.04.1989",
          tg: "@LanceThomas",
          lastLogin: "01.11.2021"
        },{
          id: 5,
          src: require("../assets/Table/a4.svg") ,
          name: "Cheryl Glover",
          team: "Gunters",
          role: 'Python Programmist',
          mail: 'cherylglover@gmail.com',
          birthday: "15.08.1985",
          tg: "@CherylGlover",
          lastLogin: "03.11.2021"
        },
        {
          id: 6,
          src: require("../assets/Table/NoAvatar2.svg") ,
          name: "Lance Thomas",
          team: "Crosty",
          role: 'Seo Specialist',
          mail: 'lancethomas@gmail.com',
          birthday: "12.04.1989",
          tg: "@LanceThomas",
          lastLogin: "01.11.2021"
        },{
          id: 7,
          src: require("../assets/Table/a2.svg") ,
          name: "Ernest Eberly",
          team: "Flamethrower",
          role: 'Semantic Specialist',
          mail: 'ernesteberly@gmail.com',
          birthday: "17.06.1993",
          tg: "@ErnestEberly",
          lastLogin: "03.11.2021"
        },{
          id: 8,
          src: require("../assets/Table/a3.svg") ,
          name: "Lance Thomas",
          team: "Wizards",
          role: 'Seo Specialist',
          mail: 'lancethomas@gmail.com',
          birthday: "12.04.1989",
          tg: "@LanceThomas",
          lastLogin: "01.11.2021"
        },
        {
          id: 9,
          src: require("../assets/Table/a4.svg") ,
          name: "Cheryl Glover",
          team: "Gunters",
          role: 'Python Programmist',
          mail: 'cherylglover@gmail.com',
          birthday: "15.08.1985",
          tg: "@CherylGlover",
          lastLogin: "03.11.2021"
        }
      ]
    }
  }
}
</script>

<style  scoped>
table{
  border-collapse: collapse;
 border-radius: 12px;
}
.thR1{
  border-radius:  12px 0  0 12px ;
}
.thR2{
  border-radius: 0 12px  12px 0 ;
}
.th1{
  width: 221.14px;
  padding: 16px;
}
.th1:not(:last-child){
  border-right: 1px solid #E5E8EF;
}
.thContainer{
  display: flex;
  align-items: center;
  max-width: 221.14px;
}
.nameTh{
  margin-right: 4px;
}
th{
  align-items: center;
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 130%;
}
.tableContainer{
  padding: 16px;
  margin-top: 28px;
  margin-left: 28px;
  background: #FFFFFF;
  width: 1792px;
  height: 680px;
  border-radius: 12px;
}
.arrowContainer{
  margin-left: 91.14px;
  width: 20px;
  height: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #FFFFFF;
  border-radius: 6px;
}
.tableHeader{
  max-width: 1760px;
  background: #F5F7FB;
  height: 64px;
}
.btnEdit{
  margin-top: 14px;
  padding-left: 16px;
  width: 78px;
  background: #FFFFFF;
  height: 36px;
  border: 1px solid #E5E8EF;
  border-radius: 8px;
  display: flex;
  align-items: center;
}
.textEditBtn{
  padding-left: 8px;
}
.userPermissionsContainer{
  display: flex;
}
.trash{
  margin-left: auto;
  margin-right: 32px;
  margin-top: 12px;
}
.rowInfo{
  height: 64px;
}
.rowInfo:not(:last-child){

  border-bottom: 1px solid #F5F7FB;
}
td{
  font-family: 'Commissioner';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  color: #2A355A;
  padding-left: 16px;
}
.ferstItem{
  display: flex;
  align-items: center;

}
.nameTD{
  margin-left: 12px;

}
</style>