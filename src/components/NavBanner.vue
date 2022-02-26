<template>
   <div id="nav" class="navigation">
        <img src="./assets/logo.svg" alt="Monterail Cinema logo" class="navigation__logo">
        <ul class="navigation__list" id="nav-ul">
            <li class="navigation__item"><a class="navigation__item-link" href="#">Register</a></li>
            <li class="navigation__item"><a class="navigation__item-link navigation__item-button" href="#">Login</a>
            </li>
            <li class="navigation__item"><img src="./assets/bars.svg" alt="hamburger menu" class="navigation__bars">
            </li>
        </ul>
    </div>
</template>

//<script>
// export default {
//   name: 'HelloWorld',
//   data () {
//     return {
//       msg: 'Welcome to Your Vue.js App'
//     }
//   }
// }
// </script>

// <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navigation {
  padding: 33px 32px;
  display: flex;
  flex-direction: row;
  align-content: center;
  justify-content: space-around;
  align-items: center; }
  @media (min-width: 1024px) {
    .navigation {
      margin: 0 48px;
      padding: 25px 0;
      display: flex;
      flex-direction: row;
      align-content: center;
      justify-content: space-between;
      align-items: center; } }
  .navigation__logo {
    width: 183.64px; }
    @media (min-width: 1024px) {
      .navigation__logo {
        width: 182.09px;
        height: 37.24px; } }
  .navigation__list {
    list-style-type: none; }
    @media (min-width: 1024px) {
      .navigation__list {
        display: flex;
        flex-direction: row; } }
  .navigation__item-link {
    display: none; }
    @media (min-width: 1024px) {
      .navigation__item-link {
        display: inline-block;
        padding: 16px 30px;
        width: 139px;
        height: 48px;
        font-family: "Roboto Mono", monospace;
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 16px;
        text-align: center;
        text-decoration: none;
        letter-spacing: 0.015em;
        color: #ec1115; } }
  .navigation__item {
    text-decoration: none; }
  .navigation__item-button {
    padding: 16px 30px;
    width: 110px;
    height: 48px;
    background: #ec1115;
    border-radius: 24px;
    color: #ffffff; }
  .navigation__bars {
    width: 32px;
    height: auto; }
    @media (min-width: 1024px) {
      .navigation__bars {
        display: none; } }
</style>
