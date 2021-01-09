<template>
  <div>
    <div class="content">
      <div class="order-food-heading">
        <h1>Order Your Food</h1>
      </div>
      <div class="menu-container">
        <div class="menu-heading">
          <h1>Today's Menu</h1>
        </div>
        <div class="menu">
          <div class="menu-item">
            <h3>Breakfast</h3>
            <ul>
              <li>Bread</li>
              <li>Butter</li>
              <li>Tea</li>
            </ul>
          </div>
          <div class="menu-item">
            <h3>Lunch</h3>
            <ul>
              <li>Rice</li>
              <li>Dal</li>
              <li>Roti</li>
              <li>CauliFlower Sabji</li>
              <li>Salad</li>
            </ul>
          </div>
          <div class="menu-item">
            <h3>Snacks</h3>
            <ul>
              <li>Tea</li>
              <li>Samosa Chat</li>
            </ul>
          </div>
          <div class="menu-item">
            <h3>Dinner</h3>
            <ul>
              <li>Roti</li>
              <li>Matar Paneer</li>
              <li>Papad</li>
              <li>Dal</li>
              <li>Kheer</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: "home"
};
</script>

<style scoped>
.content {
  padding: 32px;
}

.order-food-heading {
  margin: auto;
  padding: 16px;
  background-color: #1a192c;
  width: max-content;
  border: 3px solid #e03375;
  border-radius: 12px;
}

.order-food-heading h1 {
  font-size: 1.8rem;
  font-family: "Montserrat", sans-serif;
  color: #f8edeb;
  font-weight: 500;
}

.menu-heading {
  width: max-content;
  margin: 32px auto;
  text-align: center;
}

.menu-heading h1 {
  font-family: "Montserrat", sans-serif;
  font-weight: 600;
  font-size: 1.8rem;
  color: #880f3e;
}

.menu {
  display: flex;
  justify-content: space-around;
  align-items: stretch;
  height: 100%;
}

.menu h3 {
  font-size: 1.8rem;
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  text-align: center;
}

.menu-item {
  background: rgba(255, 255, 255, 0.3);
  padding: 16px;
  width: 320px;
}

.menu-item h3 {
  font-family: "Poppins", sans-serif;
  color: #7b2cbf;
}

ul {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  padding: 8px;
}

li {
  list-style: none;
  font-size: 1.4rem;
  margin: 32px 0;
}
</style>
