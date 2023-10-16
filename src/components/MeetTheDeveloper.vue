<template>
    <div class="meet-the-developer">
      <h2>Meet the Developer</h2>
      <img src="developer-image.jpg" alt="Developer Image" />
      <p>John Doe</p>
      <p>Full Stack Developer</p>
    </div>
  </template>
  
  <script>
  export default {
    name: "MeetTheDeveloper",
  };
  </script>
  
  <style scoped>
  .meet-the-developer {
    background-color: #e74c3c;
    color: #ecf0f1;
    text-align: center;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  }
  
  .meet-the-developer h2 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .meet-the-developer img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin: 10px;
  }
  
  .meet-the-developer p {
    margin: 5px 0;
  }
  </style>
  