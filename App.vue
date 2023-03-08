<template>
  <div class="app">
    <div class="nav-bar">
      <img src="./assets/logo.svg" alt="logo" />
      <ul class="nav-li">
        <li>home</li>
        <li>home</li>
        <li>home</li>
        <li>home</li>
        <li>home</li>
      </ul>
      <div class="dropdown">
        <a
          class="btn btn-success dropdown-toggle"
          href="#"
          role="button"
          data-bs-toggle="dropdown"
          aria-expanded="false">
          Dropdown link
        </a>

        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
        </ul>
      </div>
      <input type="text" placeholder="Search" />
      <button type="button" class="btn btn-success">Search</button>
    </div>
    <div class="nav-header">
      <div class="nav-header__img">
        <h1>Click start to <span> start</span> VUE.JS!!!</h1>
      </div>
    </div>
  </div>
  <!-- <div class="container"> -->
  <!-- <label for="name">Name:</label> -->
  <!-- <input id="name" v-modul="name" type="text" /> -->
  <!--  -->
  <!-- <label for="email">Email :</label> -->
  <!-- <input id="email" v-modul="email" type="text" /> -->
  <!--  -->
  <!-- <label for="password">Password :</label> -->
  <!-- <input id="password" v-modul="password" type="password" /> -->
  <!--  -->
  <!-- <label for="remember-me">Remember-me :</label> -->
  <!-- <input id="remember-me" v-modul="rememberMe" type="checkbox"> -->
  <!--   
  <label>Favorite color</label>
  <select v-modul="FavoritColor">
    <option value="red">red</option>
    <option value="green">green</option>
    <option value="yellow">yellow</option>
  </select> -->
  <!-- </div> -->
</template>
<script>
export default {
  //  data() {
  //  return{
  //  name:"",
  //email:"",
  //  password:"",
  //  rememberMe:"false",
  //      FavoritColor:"red",
  //   }
  //}
};
</script>
<style>
body {
  background-color: aliceblue;
  margin: 0;
}
.nav-bar {
  display: flex;
  align-items: center;
  background: linear-gradient(50deg, rgb(50, 245, 128), rgb(100, 241, 213));
  height: 70px;
  color: #fff;
}
.nav-bar img {
  width: 100px;
  height: 50px;
  margin: 10px;
}
.nav-li {
  display: flex;
  align-items: center;
  color: white;
}
.nav-li li {
  list-style-type: none;
  margin-left: 80px;
  margin-top: 15px;
}
.nav-bar input {
  height: 40px;
  border: 1px solid green;
  border-radius: 10px;
  margin-left: 50px;
}
.dropdown {
  display: flex;
  align-items: center;
  margin-left: 50px;
}
.nav-header__img {
  width: 1100px;
  height: 580px;
  color: #fff;
  font-family: Arial, Helvetica, sans-serif;
  background-image: url(./assets/vue.img.png);
}
.nav-header__img h1 {
  margin-left: 500px;
  padding-top: 100px;
}
.nav-header__img span {
  color: rgb(0, 255, 0);
}
</style>
