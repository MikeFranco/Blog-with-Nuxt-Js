<template>
  <header class="header" >
    <ul class="nav-items" >
      <li> <h1> <nuxt-link to="/" > Home </nuxt-link> </h1> </li>
      <li> <h1> <nuxt-link to="/users" > Users </nuxt-link> </h1> </li>
    </ul>
  </header>
</template>

<style scoped>
  .header{
    width: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: aqua;
  }

  .nav-items{
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 80%;
  }

  .nav-items a {
    text-decoration: none;
    color: black;
  }

  .nav-items a:hover,
  .nav-items a:active{
    color: red;
  }

</style>
