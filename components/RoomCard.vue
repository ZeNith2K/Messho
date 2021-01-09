<template>
  <div class="room-card">
    <img src="~/assets/images/room.jpg" alt="" />
    <div class="room-info">
      <div class="fields">
        <p>Room</p>
        <p>Attached Bathroom</p>
        <p>Rent</p>
      </div>
      <div class="seperator">
        <p>:</p>
        <p>:</p>
        <p>:</p>
      </div>
      <div class="details">
        <p>Single Bed</p>
        <p>Yes</p>
        <p>4000</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.room-card {
  margin: 32px 48px;
  padding: 16px;
  border: 2px solid #457b9d;
  border-radius: 12px;
  width: max-content;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: #bdddf1;
}

.room-info {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.fields,
.seperator,
.details {
  margin: 8px;
  font-family: "Montserrat", sans-serif;
  color: #3b3b3b;
}

p {
  margin: 2px;
}

img {
  height: 200px;
  width: 250px;
}
</style>
