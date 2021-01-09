<template>
  <div>
    <div class="header">
      <p class="nav-logo"><nuxt-link to="/">Messho</nuxt-link></p>
      <ul class="nav">
        <nuxt-link to="/login"><li class="nav-links">Login</li></nuxt-link>
        <nuxt-link to="/signup"><li class="nav-links">Signup</li></nuxt-link>
      </ul>
    </div>
    <div class="container">
      <Nuxt />
    </div>
    <div class="footer">
      Copyright @ Messho®
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&family=Poppins:wght@400;500;600;700&family=Roboto:wght@400;500;700&display=swap");

html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

body {
  margin: 0;
  padding: 0;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.header {
  height: 6vh;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 24px;
  background-color: #1a192c;
  color: #d1d1d1;
}

.nav {
  list-style: none;
}

.nav-logo {
  margin: 16px;
  font-size: 2rem;
}

.nav-links {
  display: inline;
  margin: 16px;
  border: 2px solid turquoise;
  padding: 5px 10px;
  border-radius: 8px;
  font-size: 1.2rem;
}

a {
  text-decoration: none;
  color: inherit;
}

.nav-links:hover {
  background-color: turquoise;
  color: #0f0f0f;
  cursor: pointer;
}

.footer {
  height: 4vh;
  background-color: #03bfcb;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
}
</style>
