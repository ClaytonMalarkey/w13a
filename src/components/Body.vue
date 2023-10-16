<template>
    <div class="body">
      <div class="main-content">
        <div class="sub-component">
          <SidePanel />
        </div>
        <div class="sub-component">
          <MeetTheDeveloper />
        </div>
        <div class="sub-component">
          <MeetTheTeam />
        </div>
      </div>
    </div>
  </template>
  
  <script>
  import SidePanel from "./SidePanel.vue";
  import MeetTheDeveloper from "./MeetTheDeveloper.vue";
  import MeetTheTeam from "./MeetTheTeam.vue";
  
  export default {
    name: "AppBody",
    components: {
      SidePanel,
      MeetTheDeveloper,
      MeetTheTeam,
    },
  };
  </script>
  
  <style scoped>
  .body {
    background-color: #f2f2f2;
    padding: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .main-content {
    display: flex;
    justify-content: space-between;
  }
  
  .sub-component {
    flex: 1;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
    margin: 10px;
    border-radius: 5px;
  }
  </style>
  