<template>
    <div class="meet-the-team">
      <h2>Meet the Team</h2>
      <div class="team-member">
        <img src="team-member1.jpg" alt="Team Member 1" />
        <p>Team Member 1</p>
        <p>Designer</p>
      </div>
      <div class="team-member">
        <img src="team-member2.jpg" alt="Team Member 2" />
        <p>Team Member 2</p>
        <p>Front-end Developer</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "MeetTheTeam",
  };
  </script>
  
  <style scoped>
  .meet-the-team {
    background-color: #3498db;
    color: #ecf0f1;
    text-align: center;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  }
  
  .meet-the-team h2 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .team-member {
    display: inline-block;
    margin: 20px;
  }
  
  .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
  }
  
  .team-member p {
    margin: 5px 0;
  }
  </style>
  