<template>
  <div class="navroboto-normal-white-24px">
    <div class="overlap-group"><h1 class="text-5">Главная</h1></div>
    <div class="text-4">О нас</div>
    <div class="text-3">Мастера</div>
    <div class="text-2">Контакты</div>
    <div class="phone">
      <img class="phone-icon" src="phone-icon.png" />
      <div class="text-1roboto-bold-white-24px">+380 - 956 - 96 - 03</div>
    </div>
  </div>
</template>

<script>
  export default {
    name: "App",
  };
</script>

<style>
  .nav {
    align-items: center;
    display: flex;
    min-width: 1135px;
  }

  .overlap-group {
    align-items: flex-end;
    background-color: #00efff6e;
    display: flex;
    height: 76px;
    min-width: 200px;
    padding: 13px 54px;
  }

  .text-5 {
    letter-spacing: 0;
    min-height: 28px;
    min-width: 92px;
  }

  .text-4 {
    letter-spacing: 0;
    margin-left: 22px;
    margin-top: 22px;
    min-height: 28px;
    min-width: 62px;
  }

  .text-3 {
    letter-spacing: 0;
    margin-left: 76px;
    margin-top: 22px;
    min-height: 28px;
    min-width: 97px;
  }

  .text-2 {
    letter-spacing: 0;
    margin-left: 76px;
    margin-top: 22px;
    min-height: 28px;
    min-width: 111px;
  }

  .phone {
    align-items: center;
    align-self: flex-end;
    display: flex;
    margin-bottom: 11px;
    margin-left: 205px;
    min-width: 282px;
  }

  .phone-icon {
    height: 31px;
    object-fit: cover;
    width: 31px;
  }

  .text-1 {
    letter-spacing: 0;
    margin-bottom: 1px;
    margin-left: 33px;
    min-height: 28px;
    min-width: 216px;
  }
</style>