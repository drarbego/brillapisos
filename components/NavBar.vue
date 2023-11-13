<template>
  <div class="bar__container">
    <img class= "bar__logo" src="/images/logo.webp" alt="logo">
    <div>
      <span class="bar__option">INICIO</span>
      <span class="bar__option">SERVICIOS</span>
      <span class="bar__option">CONTACTOS</span>
    </div>
    <div class="bar__phone">
      3 3 1 4 9 6 1 0 6 4
    </div>
  </div>
</template>
<style>
  .bar__container {
    background-color: #ffde11;
    height: 64px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: fixed;
  }

  .bar__logo {
    margin-left: 230px;
    height: 64px;
  }

  .bar__phone {
    margin-right: 230px;
    color: #ffffff;
    font-family: futura-lt-w01-light, futura-lt-w05-light, sans-serif;
    font-weight: bold;
    font-size: 20px;
  }

  .bar__option {
    margin-right: 20px;
    margin-left: 20px;
    font-family: brandon-grot-w01-light, brandon-grot-w05-light, sans-serif;
    font-size: 14px;
  }
</style>
