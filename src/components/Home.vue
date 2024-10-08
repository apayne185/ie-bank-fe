<template>
    <div class="homepage">
        <h1>Welcome to the IE Bank!</h1>
        <p>#1 BANK!!</p>
        <div class="links">
            <router-link to="/accounts" class="link-button">Accounts</router-link>
            <router-link to="/skull" class="link-button">Skull</router-link>
        </div>
    </div>
  </template>
  
  <script>
  export default {
      name: "Home Page",
  }
  </script>
  <style scoped>
  .homepage {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background-color: white;
      width: 100%;
      height: 100vh;
  }
  h1 {
      font-size: 78px;
      background: -webkit-linear-gradient(right, #ffc0cb, #ff748c);
      -webkit-background-clip: text;
      background-clip: text;
      -webkit-text-fill-color: transparent;
      color: transparent; 
  }
  p {
      color: #8b7575;
      font-size: 18px;
  }
  .links {
      display: flex;
      width: 100%;
      justify-content: center;
      gap: 20px;
  }
  
  .link-button {
    padding: 12px 24px;
    background-color: #8b7575;
    color: white;
    text-decoration:none;
    border-radius: 5px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition:background-color 0.3s, transform 0.2s;
  }

  .link-button:hover {
    background-color: #766363; 
    transform: translateY(-2px); 
}

  </style>