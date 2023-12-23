<template>
  <div class="globalWrapper">
    <header class="header">
      <div class="header__wrapper">
        <div class="header__logo">
          <p class="header__logo-item">
            BrandName
          </p>
        </div>
        <nav class="header__nav">
          <ul class="header__list">
            <li class="header__item">
              <p class="header__item-text">
                Home
              </p>
            </li>
            <li class="header__item">
              <p class="header__item-text">
                Product
              </p>
            </li>
            <li class="header__item">
              <p class="header__item-text">
                Pricing
              </p>
            </li>
            <li class="header__item">
              <p class="header__item-text">
                Contact
              </p>
            </li>
          </ul>
        </nav>
      </div>
    </header>

    <body>
      <div class="mainWrapper__wrapper">
        <div class="mainWrapper__mainText">
          <p class="mainWrapper__mainText-item">
            We Ensure A Best Insurance Service
          </p>
        </div>
        <div class="mainWrapper__underMainText">
          <p class="mainWrapper__underMainText-item">
            We know how large objects will act, but things on a small scale just do not act that way.
          </p>
        </div>
        <div class="mainWrapper__btns">
          <div class="mainWrapper__btns-left">
            <p class="mainWrapper__btns-left-item"> Get Quote Now</p>
          </div>
          <div class="mainWrapper__btns-right">
            <p class="mainWrapper__btns-right-item"> Learn More </p>
          </div>
        </div>
      </div>
    </body>
  </div>
</template>

<script>

import "@fontsource/montserrat";

export default {
  name: 'headerMain',
}
</script>

<style>
.globalWrapper {
  background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../static/header__wrapper.svg);
  background-repeat: no-repeat;
  background-size: cover;
  height: 793px;
  overflow: hidden;
}

.header__wrapper {

  display: flex;

  flex-wrap: wrap;
  justify-content: flex-start;
  padding: 20px;
}

.header__logo-item {
  color: #FFF;
  font-family: Montserrat;
  font-size: 24px;
  font-style: normal;
  font-weight: 700;
  line-height: 32px;
  letter-spacing: 0.1px;
}

.header__list {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.header__item {
  list-style-type: none;
  margin-right: 32px;
}


.header__item-text {
  color: #FFF;
  text-align: center;
  font-family: Montserrat;
  font-size: 14px;
  font-style: normal;
  font-weight: 600;
  line-height: 24px;
  letter-spacing: 0.2px;
}

.mainWrapper__wrapper {
  margin-top: 43px;
  display: flex;
  align-content: center;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: column;
}

.mainWrapper__mainText {
  width: 695px;
}

.mainWrapper__mainText-item {
  color: #FFF;
  text-align: center;
  font-family: Montserrat;
  font-size: 58px;
  font-style: normal;
  font-weight: 800;
  line-height: 80px;
  letter-spacing: 0.2px;
}

.mainWrapper__underMainText {
  width: 539px;
}

.mainWrapper__underMainText-item {
  color: #FFF;
  text-align: center;
  font-family: Montserrat;
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 30px;
  letter-spacing: 0.2px;

}

.mainWrapper__btns {
  display: flex;
}

.mainWrapper__btns-left {
  border-radius: 37px;
  background: var(--primary-color, #23A6F0);
  margin-right: 10px;
  display: flex;
  padding: 0px 21px;
  flex-direction: column;
  align-items: center;
}

.mainWrapper__btns-left-item {
  color: var(--light-text-color, #FFF);
  text-align: center;
  /* btn-text */
  font-family: Montserrat;
  font-size: 14px;
  font-style: normal;
  font-weight: 700;
  line-height: 22px;
  /* 157.143% */
  letter-spacing: 0.2px;
}

.mainWrapper__btns-right {
  border-radius: 37px;
  border: 1px solid var(--light-text-color, #FFF);
  display: flex;
  padding: 0px 21px;
  flex-direction: column;
  align-items: center;
}

.mainWrapper__btns-right-item {
  color: var(--light-text-color, #FFF);
  text-align: center;
  /* btn-text */
  font-family: Montserrat;
  font-size: 14px;
  font-style: normal;
  font-weight: 700;
  line-height: 22px;
  /* 157.143% */
  letter-spacing: 0.2px;
}

@media (max-width: 375.98px) {
  .globalWrapper {
    background-size: auto 100%;
    background-position: center;
  }
  .mainWrapper__mainText {
    width: 310px;
  }
  .mainWrapper__underMainText {
    width: 310px;
  }

  .mainWrapper__mainText-item {
    color: var(--light-text-color, #FFF);
    text-align: center;
    /* h2 */
    font-family: Montserrat;
    font-size: 40px;
    font-style: normal;
    font-weight: 700;
    line-height: 57px;
    /* 142.5% */
    letter-spacing: 0.2px;
  }

  .mainWrapper__underMainText-item {
    color: var(--light-text-color, #FFF);
    text-align: center;
    /* h4 */
    font-family: Montserrat;
    font-size: 20px;
    font-style: normal;
    font-weight: 500;
    line-height: 30px;
    /* 150% */
    letter-spacing: 0.2px;
  }

}
</style>
