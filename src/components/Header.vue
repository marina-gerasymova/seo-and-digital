<template>
  <header class="header">
    <a href="#" class="header__logo-wraper logo">
      <img src="../image/Logo.svg" alt="GrowBe" class="header__logo" />
    </a>

    <div class="header__nav nav">
      <ul class="nav__list">
        <li class="nav__item"><a href="#" class="nav__link">Home</a></li>
        <li class="nav__item"><a href="#" class="nav__link">About us</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Services</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Features</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Team</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Blog</a></li>
        <li class="nav__item"><a href="#" class="nav__link">Contact</a></li>
      </ul>

      <a href="#" class="nav__button button">Get Started</a>

      <div class="header__burger burger">
        <input type="checkbox" id="nav-trigger" class="burger__trigger" />
        <label for="nav-trigger" class="burger__icon"></label>

        <div class="burger__menu">
          <ul class="burger__list">
            <li class="burger__item">
              <a href="#" class="burger__link">Home</a>
            </li>
            <li class="burger__item">
              <a href="#" class="burger__link">About us</a>
            </li>
            <li class="burger__item">
              <a href="#" class="burger__link">Services</a>
            </li>
            <li class="burger__item">
              <a href="#" class="burger__link">Features</a>
            </li>
            <li class="burger__item">
              <a href="#" class="burger__link">Team</a>
            </li>
            <li class="burger__item">
              <a href="#" class="burger__link">Blog</a>
            </li>
            <li class="burger__item">
              <a href="#" class="burger__link">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>
