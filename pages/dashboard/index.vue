<template>
  <div class="content">
    <div class="first-div">
      <div class="student-details">
        <h1 class="student-heading">Student Details</h1>
        <div class="student-div">
          <div class="fields">
            <p>Name</p>
            <p>Email</p>
            <p>Phone</p>
            <p>Year</p>
            <p>Roll</p>
          </div>
          <div class="seperator">
            <p>:</p>
            <p>:</p>
            <p>:</p>
            <p>:</p>
            <p>:</p>
          </div>
          <div class="details">
            <p>Sumit</p>
            <p>sumitpks99@gmail.com</p>
            <p>9801278051</p>
            <p>3rd</p>
            <p>12500118010</p>
          </div>
        </div>
      </div>
      <div class="lodging-details">
        <h1 class="lodging-heading">Lodging Details</h1>
        <div class="lodging-div">
          <div class="fields">
            <p>Room</p>
            <p>Room No.</p>
            <p>Monthly Bill</p>
            <p>Bills</p>
          </div>
          <div class="seperator">
            <p>:</p>
            <p>:</p>
            <p>:</p>
            <p>:</p>
          </div>
          <div class="details">
            <p>2 Bed Lodging</p>
            <p>403</p>
            <p>Rs 3000</p>
            <p>Paid</p>
          </div>
        </div>
      </div>
    </div>
    <div class="second-div">
      <div class="fooding-details">
        <h1 class="fooding-heading">Fooding Details</h1>

        <div class="fooding-div">
          <div class="fields">
            <p>Fooding</p>
            <p>Monthly Bill</p>
            <p>Bills</p>
          </div>
          <div class="seperator">
            <p>:</p>
            <p>:</p>
            <p>:</p>
          </div>
          <div class="details">
            <p>Non-Veg</p>
            <p>Rs 2000</p>
            <p>Paid</p>
          </div>
        </div>
        <img src="~/assets/images/food.jpg" alt="" />
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
  padding: 50px;
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.first-div {
  width: 60%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

.second-div {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100%;
}

.student-details {
  width: 100%;
  padding: 32px;
  border: 2px solid #2972a0;
  border-radius: 8px;
  background: #bdddf1;
}

.student-details h1 {
  margin-bottom: 24px;
  font-size: 3rem;
  font-weight: 500;
  color: #83321e;
  font-family: "Poppins", sans-serif;
  text-align: center;
}

.student-div {
  margin: auto;
  width: 60%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.student-div .fields p {
  font-size: 1.1rem;
  font-family: "Montserrat", sans-serif;
  color: #83321e;
  font-weight: 500;
}

.student-div .details p {
  font-size: 1.1rem;
  font-family: "Montserrat", sans-serif;
  color: #3a3a3a;
  font-weight: 500;
}

.lodging-details {
  width: 100%;
  padding: 32px;
  border: 2px solid #2972a0;
  border-radius: 8px;
  background: #bdddf1;
}

.lodging-details h1 {
  margin-bottom: 24px;
  font-size: 3rem;
  font-weight: 500;
  color: #1960d3;
  font-family: "Poppins", sans-serif;
  text-align: center;
}

.lodging-div {
  margin: auto;
  width: 60%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.lodging-div .fields p {
  font-size: 1.1rem;
  font-family: "Montserrat", sans-serif;
  color: #1960d3;
  font-weight: 500;
}

.lodging-div .details p {
  font-size: 1.1rem;
  font-family: "Montserrat", sans-serif;
  color: #3a3a3a;
  font-weight: 500;
}

.fooding-details {
  width: 100%;
  height: 100%;
  padding: 32px;
  border: 2px solid #2972a0;
  border-radius: 8px;
  background: #bdddf1;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
}

.fooding-details h1 {
  margin-bottom: 24px;
  font-size: 3rem;
  font-weight: 500;
  color: #ac7800;
  font-family: "Poppins", sans-serif;
  text-align: center;
}

.fooding-div {
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.fooding-div .fields p {
  font-size: 1.1rem;
  font-family: "Montserrat", sans-serif;
  color: #ac7800;
  font-weight: 500;
}

.fooding-div .details p {
  font-size: 1.1rem;
  font-family: "Montserrat", sans-serif;
  color: #3a3a3a;
  font-weight: 500;
}

p {
  margin-bottom: 8px;
}

img {
  width: 350px;
  height: 250px;
  margin: 32px;
  border-radius: 16px;
}
</style>
