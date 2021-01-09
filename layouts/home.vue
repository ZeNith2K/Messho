<template>
  <div>
    <div class="header">
      <p class="nav-logo"><nuxt-link to="/">Messho</nuxt-link></p>
      <ul class="nav">
        <nuxt-link to="/login"><li class="nav-links">Login</li></nuxt-link>
        <nuxt-link to="/signup"><li class="nav-links">Signup</li></nuxt-link>
      </ul>
    </div>
    <div class="mid-container">
      <div class="sidenav">
        <ul>
          <nuxt-link to="/dashboard"
            ><li class="sidenav-links">Dashboard</li></nuxt-link
          >
          <nuxt-link to="/lodging"
            ><li class="sidenav-links">Lodging Options</li></nuxt-link
          >
          <nuxt-link to="/your-room"
            ><li class="sidenav-links">Your Room</li></nuxt-link
          >
          <nuxt-link to="/order-food"
            ><li class="sidenav-links">Order Food</li></nuxt-link
          >
          <nuxt-link to="/pay-bill"
            ><li class="sidenav-links">Pay Bill</li></nuxt-link
          >
          <nuxt-link to="/order-history"
            ><li class="sidenav-links">Order History</li></nuxt-link
          >
        </ul>

        <button class="admin-button">Admin</button>
      </div>
      <div class="container">
        <nuxt />
      </div>
    </div>

    <div class="footer">
      Copyright @ Messho®
    </div>
  </div>
</template>

<style scoped>
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

.mid-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 16px;
  height: 90vh;
}

.sidenav {
  background-color: #1a192c;
  width: 300px;
  height: 100%;
  border-radius: 12px;
  padding: 32px 16px;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

li {
  list-style: none;
  margin-bottom: 32px;
  font-size: 1.1rem;
}

.admin-button {
  height: 40px;
  width: 12vw;
  margin: 0 auto;
  background-color: #dd6847;
  font-size: 1.1rem;
  color: white;
  border: 2px solid whitesmoke;
  border-radius: 8px;
}

.admin-button:focus {
  outline: none;
}

.admin-button:hover {
  cursor: pointer;
}

.container {
  height: 100%;
  width: 100%;
  background-color: #7baac7;
  margin-left: 16px;
  border-radius: 12px;
  padding: 16px;
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
