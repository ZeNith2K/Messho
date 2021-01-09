<template>
  <div class="container">
    <div class="circle red"></div>
    <div class="circle yellow"></div>
    <div class="circle blue"></div>
    <div class="circle green"></div>
    <div class="square pink"></div>
    <div class="square orange"></div>
    <div class="brand">
      <h1>Messho</h1>
      <h2>Mess Management System</h2>
      <h3>Track all your food expenses with our robust services !!</h3>
    </div>
    <div class="about">
      <h1>About Us</h1>
      <div class="cards">
        <div class="sumit">
          <div class="card-container">
            <img class="round" src="~/assets/images/oreki.jpg" alt="user" />
            <h3>Sumit Kumar</h3>
            <h6>CSE B</h6>
            <p>
              User interface designer, android and <br />
              full stack developer.
            </p>
            <div class="buttons">
              <button class="primary">
                Github
              </button>
              <button class="primary ghost">
                Facebook
              </button>
            </div>
            <div class="skills">
              <h6>Skills</h6>
              <ul>
                <li>UI / UX</li>
                <li>Front End Development</li>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>React</li>
                <li>Node</li>
                <li>Vue</li>
                <li>Nuxt</li>
                <li>Next</li>
                <li>Flutter</li>
              </ul>
            </div>
          </div>
        </div>
        <div class="sandeep">
          <div class="card-container san">
            <img class="round" src="~/assets/images/sandeep.jpg" alt="user" />
            <h3>Sandip Sadhukhan</h3>
            <h6>CSE B</h6>
            <p>
              Full stack web <br />
              developer.
            </p>
            <div class="buttons">
              <button class="primary">
                Github
              </button>
              <button class="primary ghost">
                Facebook
              </button>
            </div>
            <div class="skills">
              <h6>Skills</h6>
              <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>React</li>
                <li>Node</li>
                <li>Flutter</li>
                <li>Socket</li>
                <li>Django</li>
                <li>MongoDb</li>
                <li>PostgresSql</li>
                <li>Front End Development</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.container {
  text-align: center;
  background-color: #1a192c;
  color: white;
  padding: 100px 100px;
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

.brand {
  padding: 50px;
  margin: 0 0 100px;
}

.brand h1 {
  margin: 50px;
  font-family: "Montserrat", sans-serif;
  font-size: 4.5rem;
  color: #5bc0be;
}

.brand h2 {
  margin: 50px;
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  font-size: 2rem;
}

.brand h3 {
  margin: 50px;
  font-family: "Poppins", sans-serif;
  font-weight: 400;
}

.about {
  background-color: #41597c;
  padding: 50px;
  border-radius: 16px;
}

.about h1 {
  margin: 0 0 30px;
  font-family: "Poppins", sans-serif;
  font-size: 3rem;
  color: #68d4d3;
}

.cards {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

h3 {
  margin: 10px 0;
}

h6 {
  margin: 5px 0 10px;
  text-transform: uppercase;
}

p {
  font-size: 14px;
  line-height: 21px;
  margin: 0 0 8px;
}

img {
  border-radius: 50%;
  height: 200px;
  width: 200px;
}

.card-container {
  background-color: #aed9e0;
  border-radius: 5px;
  box-shadow: 0px 10px 20px -10px rgba(0, 0, 0, 0.6);
  color: #b3b8cd;
  padding-top: 30px;
  position: relative;
  width: 400px;
  max-width: 100%;
  text-align: center;
  color: black;
}

.san {
  background-color: #c1d3fe;
}

.card-container .round {
  border: 2px solid #03bfcb;
  border-radius: 50%;
  padding: 7px;
}

button.primary {
  background-color: #03bfcb;
  border: 1px solid #03bfcb;
  border-radius: 3px;
  color: #231e39;
  font-family: Montserrat, sans-serif;
  font-weight: 500;
  padding: 10px 25px;
}

button.primary.ghost {
  background-color: transparent;
  color: #02899c;
}

.skills {
  background-color: #1f1a36;
  text-align: left;
  padding: 15px;
  margin-top: 30px;
  color: #c1c1c1;
}

.skills ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.skills ul li {
  border: 1px solid #2d2747;
  border-radius: 2px;
  display: inline-block;
  font-size: 12px;
  margin: 0 7px 7px 0;
  padding: 7px;
}
</style>
