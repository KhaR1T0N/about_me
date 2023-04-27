<template>
  <header class="header">
    <div class="container">
      <h1 class="header__title">PROWEB</h1>
      <ul class="header__menu">
        <li class="header__link">Обо мне</li>
        <li class="header__link">Мои работы</li>
        <li class="header__link">Контакты</li>
      </ul>
    </div>
    <div class="main__banner">
      <p class="main__banner-title">Добро пожаловать на мой сайт</p>
      <button class="main__banner-btn">Позвонить</button>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
.header {
  background: #000000;
  /* max-height: 76px; */
}

.header .container {
  display: flex;
  justify-content: space-between;
}

.header__title {
  font-weight: 700;
  font-size: 40px;
  line-height: 48px;
  color: #ffffff;
  margin: 14px 0;
}

.header__menu {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 75px;
}

.header__link {
  font-weight: 400;
  font-size: 25px;
  line-height: 30px;
  margin: 20px 0 26px 0;
  color: #ffffff;
}
.main__banner {
  background: url("../assets/img/Banner.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  height: 850px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 161px;
}
.main__banner-title {
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 700;
  font-size: 40px;
  line-height: 48px;
  color: #000000;
}

.main__banner-btn {
  font-weight: 700;
  font-size: 35px;
  line-height: 42px;
  color: #000000;
  padding: 10px 24px;
  background: #ffffff;
  border-radius: 10px;
  display: flex;
  justify-content: center;
  border: none;
}
</style>