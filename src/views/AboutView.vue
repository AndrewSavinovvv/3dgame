<script setup>

</script>

<template>
  <div class="hero-about container">
    <div class="info">
      <h1>Lorem Ipsum is simply dummy text of the printing and.</h1>
      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</p>
      <button class="btn">Get in touch</button>
    </div>
    <img src="@/assets/img/Rectangle%206.png" alt="">
  </div>
  <div class="container work">
    <h2>Work work work</h2>
    <div class="blocks">
      <div class="block">
        <span class="badge purple">Loren loren</span>
        <h3>Loreeeeen</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</p>
      </div>
      <div class="block">
        <span class="badge brown">Loren loren</span>
        <h3>Loreeeeen</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</p>
      </div>
      <div class="block">
        <span class="badge green">Loren loren</span>
        <h3>Loreeeeen</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  overflow-x: hidden;
}
.hero-about {
  position: relative;
}
.hero-about img {
  position: absolute;
  right: -150px;
  top: 0;
}
.hero-about .info {
  width: 500px;
  padding: 250px 0;
}
.hero-about .info h1 {
  margin-bottom: 15px;
  font-size: 30px;
}
.hero-about .info .btn {
  cursor: pointer;
  border: none;
  padding: 13px 17px;
  background: #25211D;
  position: relative;
  z-index: 2;
  color: white;
  margin-top: 20px;
}
.work {
  padding: 80px 0;
}
.work h2 {
  font-size: 25px;
  margin-bottom: 40px;
}
.work .blocks {
  display: flex;
  justify-content: space-between;
}
.work .blocks block {
  width: 25%;
  border-radius: 10px;
  padding: 50px 35px;
  background: #1C140F;
}
.work .blocks block h3{
  font-size: 20px;
  margin: 20px 0;
}
.work .blocks block .badge {
  border-radius: 7px;
  padding: 10px 20px;
}
.work .blocks block .badge .purple {
  background: #560F67;
}
.work .blocks block .badge .brown {
  background: brown;
}
.work .blocks block .badge .green {
  background: green;
}
</style>