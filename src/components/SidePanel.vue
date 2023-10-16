<template>
    <div class="side-panel">
      <h2>Side Panel</h2>
      <p>Explore our amazing features:</p>
      <ul>
        <li>Feature 1</li>
        <li>Feature 2</li>
        <li>Feature 3</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: "SidePanel",
  };
  </script>
  
  <style scoped>
  .side-panel {
    background-color: #2c3e50;
    color: #ecf0f1;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  }
  
  .side-panel h2 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .side-panel ul {
    list-style: none;
    padding: 0;
  }
  
  .side-panel li {
    margin: 5px 0;
  }
  </style>
  