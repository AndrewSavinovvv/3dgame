<script setup>

</script>

<template>
  <div class="container hero-contacts">
    <h1>Lorem Ipsum is simply dummy text of the printing and.</h1>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. </p>
    <img src="@/assets/img/Huge%20Global.png" alt="">
  </div>
  <div class="feedback">
    <div class="container">
      <h2>Say hello</h2>
      <p>djjdfg fdidpfgpdfg jodfoggdfiog igdfgidikfg</p>

      <form action="">
        <div class="inline">
          <div>
            <label for="">Firsrt name</label>
            <input type="text">
          </div>
          <div>
            <label for="">Last name</label>
            <input type="text">
          </div>
        </div>

        <label for="">Email address</label>
        <input class="one-line" type="text">

        <label>Massege</label>
        <textarea class="one-line"></textarea>

        <button type="button">Get in touch</button>
      </form>
    </div>
  </div>
</template>

<style scoped>
.hero-contacts h1 {
  text-align: center;
  margin-top: 70px;
  margin-bottom: 30px;
  font-size: 33px;
}
.hero-contacts p {
  text-align: center;
}
.hero-contacts img {
  width: 70%;
  margin: 80px 15%;
}
.feedback {
  padding: 70px 0;
  background: #1C140F;
}
.feedback h2 {
  text-align: center;
  font-weight: 500;
  font-size: 30px;
}
.feedback p {
  text-align: center;
  margin-top: 10px;
}
.feedback form {
  margin: 80px auto;
  width: 600px;
}
.feedback form .inline {
  display: flex;
  justify-content: space-between;
}
.feedback form .inline>div {
  width: 50%;
}
.feedback form label {
  color: #4F4F4F;
  font-size: 14px;
}
.feedback form input, .feedback form textarea {
  background: #2C2420;
  border-radius: 10px;
  border: 0.6px solid #CECECE;
  display: block;
  width: 90%;
  padding: 15px 10px;
  outline: none;
  color: white;
  margin-top: 7px;
  margin-bottom: 20px;
}
.feedback form .one-line {
  width: 96%;
}
.feedback form textarea {
  resize: none;
  height: 200px;
}
.feedback form button {
  background: orange;
  border-radius: 5px;
  border: none;
  float: right;
  cursor: pointer;
  color: white;
  padding: 15px 35px;
  transition: all 500ms ease;
}
.feedback form button:hover {
  background: red;
}
</style>