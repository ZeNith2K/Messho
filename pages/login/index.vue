<template>
  <div class="container">
    <div class="circle red"></div>
    <div class="circle yellow"></div>
    <div class="circle blue"></div>
    <div class="circle green"></div>
    <div class="square pink"></div>
    <div class="square orange"></div>
    <h1>Messho</h1>
    <div class="form-container">
      <form class="form" action="/" method="POST">
        <label for="username">User ID / Email</label>
        <input type="text" name="username" id="username" />
        <label for="password">Password</label>
        <input type="text" name="password" id="password" />
        <button type="submit">Login</button>
      </form>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.container {
  height: 90vh;
  background-color: #1a192c;
  color: #d1d1d1;
  text-align: center;
  padding: 50px;
}

.circle {
  border-radius: 50%;
  z-index: 1000;
}

.red {
  border: 2px solid red;
  height: 30px;
  width: 30px;
  position: absolute;
  top: 120px;
  left: 550px;
}

.yellow {
  background-color: yellow;
  height: 40px;
  width: 40px;
  position: absolute;
  top: 320px;
  left: 220px;
}

.green {
  background-color: yellowgreen;
  height: 30px;
  width: 30px;
  position: absolute;
  top: 220px;
  right: 250px;
}

.blue {
  background-color: lightblue;
  height: 30px;
  width: 30px;
  position: absolute;
  top: 550px;
  right: 350px;
}

.pink {
  background-color: pink;
  height: 80px;
  width: 80px;
  position: absolute;
  top: 365px;
  right: 550px;
}

.orange {
  background-color: rgb(250, 204, 118);
  height: 100px;
  width: 100px;
  position: absolute;
  top: 465px;
  left: 350px;
}

.container h1 {
  margin: 50px;
  font-size: 4rem;
  font-family: "Poppins", sans-serif;
  color: #5bc0be;
  font-weight: 600;
}

.form-container {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: #41597c;
  padding: 32px;
  border: 2px solid transparent;
  border-radius: 16px;
}

label {
  font-size: 1.2rem;
  font-family: "Roboto", sans-serif;
}

input {
  margin: 10px 0 32px;
  width: 350px;
  height: 50px;
  border-radius: 16px;
  font-size: 1.3rem;
  padding: 8px 16px;
}

input:active,
:focus {
  outline: none;
}

button {
  margin-top: 28px;
  width: 100px;
  height: 40px;
  font-size: 1.3rem;
  border: 3px solid transparent;
  border-radius: 8px;
  background-color: #e98f79;
  color: white;
}

button:hover {
  cursor: pointer;
}
</style>
