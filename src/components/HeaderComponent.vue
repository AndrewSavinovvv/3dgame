<script setup>
function checkEmail() {
  let email = document.querySelector('#email').value;
  if (!email.includes('@')) alert('Email address is required!');
  else if(!email.includes('.')) alert('Email address is required!');
  else alert("vse ok")

}
</script>

<template>
  <div class="wrapper">
    <header class="container">
      <router-link to="/">
        <span class="logo">logo</span>
      </router-link>
      <nav>
        <ul>
          <li class="active"><router-link to="/">Home</router-link></li>
          <li><router-link to="/about">About us</router-link></li>
          <li>Portfolio</li>
          <li>News</li>
          <li class="btn"><router-link to="/contacts">Contacts</router-link></li>
        </ul>
      </nav>
    </header>
    <div class="hero container">
      <div class="hero--info">
        <h2>3D game Dev</h2>
        <h1>Work that we produce for our clients</h1>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard.</p>
        <button class="btn">Get more details</button>
      </div>
      <img src="@/assets/icons/Group%201321.svg" alt="">
    </div>
    <div class="container trending">
      <a href="" class="see-all">SEE ALL</a>
      <h3>Currently Trending Games</h3>
      <div class="games">
        <div class="block">
          <img src="@/assets/img/game.png" alt="">
          <span>
            <img src="@/assets/icons/icon.png" alt="">40 Followers
          </span>
        </div>
        <div class="block">
          <img src="@/assets/img/game.png" alt="">
          <span>
            <img src="@/assets/icons/icon.png" alt="">40 Followers
          </span>
        </div>
        <div class="block">
          <img src="@/assets/img/game.png" alt="">
          <span>
            <img src="@/assets/icons/icon.png" alt="">40 Followers
          </span>
        </div>
        <div class="block">
          <img src="@/assets/img/game.png" alt="">
          <span>
            <img src="@/assets/icons/icon.png" alt="">40 Followers
          </span>
        </div>
      </div>
    </div>

    <div class="container big-text">
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
    </div>
    <div class="container banner">
      <h3>Lorem Ipsum</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,</p>
      <img src="@/assets/img/big.png" alt="">
    </div>
  </div>
  <div class="features">
    <div class="container">
      <h3>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</h3>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,</p>
      <div class="info">
        <div class="block">
          <img src="@/assets/img/12.png" alt="">
          <p>Mobile Game Development</p>
          <img src="@/assets/img/arrow%201.png" alt="">
        </div>
        <div class="block">
          <img src="@/assets/img/12.png" alt="">
          <p>Mobile Game Development</p>
          <img src="@/assets/img/arrow%201.png" alt="">
        </div>
        <div class="block">
          <img src="@/assets/img/12.png" alt="">
          <p>Mobile Game Development</p>
          <img src="@/assets/img/arrow%201.png" alt="">
        </div>
        <div class="block">
          <img src="@/assets/img/12.png" alt="">
          <p>Mobile Game Development</p>
          <img src="@/assets/img/arrow%201.png" alt="">
        </div>
        <div class="block">
          <img src="@/assets/img/12.png" alt="">
          <p>Mobile Game Development</p>
          <img src="@/assets/img/arrow%201.png" alt="">
        </div>
        <div class="block">
          <img src="@/assets/img/12.png" alt="">
          <p>Mobile Game Development</p>
          <img src="@/assets/img/arrow%201.png" alt="">
        </div>
      </div>
    </div>
  </div>
  <div class="wrapper">
    <div class="container projects">
      <h3>Our Recent Projects</h3>
    </div>
    <div class="wrapper">
      <div class="container projects">
        <h3>Our Recent Projects</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
        <div class="images">
          <img src="@/assets/img/Rectangle%2015.png" alt="">
          <img src="@/assets/img/Rectangle%2015.png" alt="">
          <img src="@/assets/img/Rectangle%2015.png" alt="">
        </div>

        <div class="images">
          <img src="@/assets/img/Rectangle%2019.png" alt="">
          <img src="@/assets/img/Rectangle%2018.png" alt="">
          <img src="@/assets/img/Rectangle%2020.png" alt="">
        </div>
        <a href="" class="see-all">SEE ALL</a>
      </div>
      <div class="container email">
        <h3>Loren loren</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
        <div class="block">
          <div>
            <h4>Stay in the loop</h4>
            <p>Subscribe to receive the latest news and updates about TDA.
              We promise not to spam you! </p>
          </div>
          <div>
            <input type="email" placeholder="Enter email address" name="email" id="email" />
            <button @click="checkEmail()" class="btn">Continue</button>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <div class="blocks container">
        <div>
        <span class="logo">
          LOGO
        </span>
          <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
        </div>
        <div>
          <h4>About us</h4>
          <ul>
            <li>Zeus</li>
            <li>Portfolio</li>
            <li>Careers</li>
            <li>Contact us</li>
          </ul>
        </div>
        <div>
          <h4>Contacts us</h4>
          <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
          <p>0983445893</p>
        </div>
      </div>
      <hr>
      <p>Copu 2021 all rigrt ggrhhdr</p>
    </footer>
  </div>
</template>

<style scoped>
header {
  padding: 50px 0;
}
header .logo {
  text-transform: uppercase;
  font-size: 29px;
  font-weight: 800;
  color: white;
}
header nav {
  float: right;
  width: 50%;
}
header nav ul {
  list-style: none;
  display: flex;
  justify-content: space-between;
  z-index: 2;
  position: relative;
}
header nav ul li {
  display: inline-block;
  color: white;
}
header nav ul li.active::after {
  content: "";
  display: block;
  width: 40px;
  height: 5px;
  background:  #DC7000;
  border-radius: 10px;
  position: relative;
  top: 10px;
  left: -15px;
}
header nav ul li a {
  color: white;
}
header nav ul li:not(.active):not(.btn) a:hover {
  border-bottom: 5px solid #DC7000;
}
header nav ul li.btn a {
  background: #FA9021;
  padding: 9px 17px;
  border-radius: 5px;
  transition: all 500ms ease;
}
header nav ul li.btn a:hover {
  background: #ff0000;
}

.hero {
  padding-bottom: 100px;
  position: relative;
  z-index: 1;
}
.hero--info {
  width: 530px;
  padding-top: 70px;
}
.hero--info h2 {
  font-weight: 600;
  font-size: 20px;
  color: #E87D0E;
}
.hero--info h1 {
  font-weight: 600;
  font-size: 50px;
}
.hero--info p {
  font-weight: 500;
  line-height: 170%;
  margin: 30px 0;
}
.hero--info .btn {
  background: #FA8305;
  color: #fff;
  border-radius: 50px;
  padding: 15px 30px;
  border: none;
  transition: all 500ms ease;
  font-size: 18px;
}
.hero--info .btn:hover {
  cursor: pointer;
  transform: scale(1.1);
}
.hero img {
  position: absolute;
  top: -150px;
  right: 0;
}
.trending {
  padding-top: 50px;
}
.trending h3 {
  font-weight: 600;
  font-size: 31px;

}
.trending .see-all {
  color: white;
  background: #25211D;
  border-radius: 5px;
  padding: 12px 23px;
  float: right;
  display: block;
  cursor: pointer;
  transition: all 500ms ease;
}
.trending .see-all:hover {
  transform: scale(1.1);
}
.trending .games {
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: 50px 0;
}
.trending .games span {
  display: block;
  text-align: center;
  margin-top: 50px;
}
.trending .games span img{
  position: relative;
  top: 5px;
  margin-right: 10px;
}
.big-text {
  padding: 50px 0;
  font-size: 35px;
  font-weight: 600;
  text-align: center;
  width: 800px;
}
.banner {
  padding: 80px 0;
}
.banner h3 {
  font-size: 30px;
  font-weight: 600;
  margin-bottom: 30px;
}
.banner p {
  line-height: 170%;
  margin-bottom: 30px;
  width: 550px;
}
.banner img {
  width: 100%;
  margin-bottom: 30px;
}
.features {
  background: url("@/assets/img/bg.png") no-repeat center center fixed;
  background-size: cover;
  padding: 80px 0;
}
.features h3, .features p {
  margin-bottom: 20px;
  text-align: center;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}
.features h3 {
  font-size: 30px;
}
.features .info {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.features .info .block {
  text-align: center;
  width: 20%;
  margin: 30px 2%;
}
.features .info .block img {
  margin-bottom: 15px;
}
.projects {
  padding: 100px 0;
}
.projects h3 {
  font-size: 30px;
  text-align: center;
}
.projects p {
  margin: 40px 0;
  text-align: center;
}
.projects .images {
  display: flex;
  justify-content: space-around;
  margin-bottom: 25px;
}
.projects .see-all {
  color: white;
  background: #DC7000;
  border-radius: 5px;
  padding: 12px 23px;
  float: none;
  display: block;
  transition: all 500ms ease;
  width: 70px;
  text-align: center;
  margin: 0 auto;
}
.email {
  padding-bottom: 120px;

}
.email h3 {
  margin-top: 60px;
  font-size: 30px;
}
.email .block {
  color: white;
  background: #1C140F;
  margin-top: 30px;
  border-radius: 10px;
  padding: 40px 3%;
  width: 94%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.email .block h4 {
  font-size: 30px;
  font-weight: 500;
}
.email .block p{
  width: 500px;
}
.email .block input {
  background: white;
  outline: none;
  border: none;
  border-radius: 5px;
  width: 380px;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
  padding: 20px 30px;
  position: relative;
  right: -100px;
  z-index: 1;
  padding-right: 120px;
}
.email .block input::placeholder {
  color: #898989;
}
.email .block button {
  cursor: pointer;
  border: none;
  padding: 13px 17px;
  background: #DC7000;
  position: relative;
  z-index: 2;
  color: white;
  border-radius: 10px;
}
footer {
  background: black;
  padding: 50px 0;
}
footer .blocks {
  display: flex;
  justify-content: space-between;
}
footer .blocks .logo {
  font-size: 29px;
  font-weight: 800;
  color: white;
}
footer .blocks p {
  width: 300px;
  margin: 15px 0;
  color: white;
}
footer .blocks h4 {
  font-weight: 500;
  font-size: 17px;
  color: white;
}
footer .blocks ul {
  list-style: none;
  padding: 0;
  margin: 0;

}
footer .blocks ul li {
  margin-top: 7px;
  opacity: 0.8;
  color: white;
}
footer hr {
  margin: 30px 0;
  border: 0;
  height: 0.6px;
  background: #ccc;
}
footer > p {
  text-align: center;
}
</style>