<template>
  <div class="content">
    <div class="your-room-heading"><h1>Your Room</h1></div>
    <div class="room-container">
      <img src="~/assets/images/room.jpg" alt="" />
      <div class="room-details-container">
        <div class="room-details">
          <div class="fields">
            <p>Room</p>
            <p>Room No</p>
            <p>Attached Bathroom</p>
            <p>Rent</p>
            <p>Bills</p>
          </div>
          <div class="seperator">
            <p>:</p>
            <p>:</p>
            <p>:</p>
            <p>:</p>
            <p>:</p>
          </div>
          <div class="details">
            <p>2 Bed lodging</p>
            <p>403</p>
            <p>Yes</p>
            <p>Rs 4000</p>
            <p>Paid</p>
          </div>
        </div>
        <button>Leave Room</button>
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

.your-room-heading {
  background-color: #1a192c;
  border: 2px solid #fa5594;
  border-radius: 12px;
  margin: auto;
  width: max-content;
  padding: 16px;
}

.your-room-heading h1 {
  font-size: 1.8rem;
  font-weight: 500;
  font-family: "Montserrat", sans-serif;
  color: white;
}

.room-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

img {
  height: 600px;
  width: 600px;
  margin: 32px;
  border-radius: 12px;
}

.room-details-container {
  height: 600px;
  padding: 32px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  background: #bdddf1;
  border: 2px solid #2972a0;
  border-radius: 12px;
}

.room-details {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

p {
  font-size: 1.4rem;
  font-family: "Poppins", sans-serif;
  margin: 16px;
}

.fields p {
  color: #bc4749;
}

button {
  padding: 16px;
  letter-spacing: 2px;
  font-size: 1.4rem;
  background-color: #f0b19c;
  border: 2px solid #2972a0;
  border-radius: 12px;
  color: #1b1b1b;
  cursor: pointer;
}

button:focus {
  outline: none;
}
</style>
