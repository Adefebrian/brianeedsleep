<template>
  <div class="container">
    <img src="./assets/logo.png" alt="Logo" class="logo" />
    <h1 class="title">Airdrop Sultan Indonesia</h1>
    <a href="https://t.me/airdropsultanindonesia" target="_blank" class="join-button">Join Airdrop Sultan</a>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  padding: 0;
  background-color: black;
  color: #d18604; 
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
}

.logo {
  width: 80px; 
}

.title {
  margin: 20px 0;
  font-size: 48px; 
  font-weight: 700; 
}

.join-button {
  padding: 10px 20px;
  background-color: #d18604;
  color: black;
  text-decoration: none;
  border-radius: 5px;
  font-weight: 700; 
  transition: background-color 0.3s;
}

.join-button:hover {
  background-color: #8d5a00; 
</style>