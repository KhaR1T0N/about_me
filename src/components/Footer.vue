<template>
  <div class="footer">
    <div class="container">
      <h2 class="footer__title">Связаться со мной</h2>
      <ul class="footer__menu">
        <li>
          <a href="" class="footer__link"
            ><img src="..//assets/img/facebook-fill.svg" alt=""
          /></a>
        </li>
        <li>
          <a href="" class="footer__link"
            ><img src="..//assets/img/insta.svg" alt=""
          /></a>
        </li>
        <li>
          <a href="" class="footer__link"
            ><img src="..//assets/img/telegram-fill.svg" alt=""
          /></a>
        </li>
        <li>
          <a href="" class="footer__link"
            ><img src="..//assets/img/email.svg" alt=""
          /></a>
        </li>
        <li>
          <a href="" class="footer__link"
            ><img src="..//assets/img/whatsapp.svg" alt=""
          /></a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background: #000000;
  padding: 46px 0 62px 0;
}
footer .container {
  max-width: 243px;
}
.footer__title {
  font-family: "Montserrat";
  font-weight: 400;
  font-size: 40px;
  line-height: 49px;
  justify-content: center;
  align-items: center;
  display: flex;
  color: #ffffff;
  padding: 46px 0px 34px;
}
.footer__menu {
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 200px;
}
.footer__link {
  width: 53px;
}
</style>