<template>
  <div class="container">
    <div class="room-heading">
      <h1>Choose Your Room</h1>
    </div>
    <div class="room-catalogue">
      <RoomCard />
      <RoomCard />
      <RoomCard />
      <RoomCard />
      <RoomCard />
      <RoomCard />
    </div>
  </div>
</template>

<script>
import RoomCard from "~/components/RoomCard";
export default {
  layout: "home",
  components: {
    RoomCard
  }
};
</script>

<style scoped>
.container {
  width: 100%;
  padding: 16px;
  margin: 0;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.room-heading {
  background-color: #1a192c;
  margin-top: 16px;
  border: 2px solid #fa5594;
  border-radius: 8px;
}

.container h1 {
  margin: 16px;
  font-size: 1.5rem;
  color: #d1d1d1;
  font-weight: 500;
  font-family: "Poppins", sans-serif;
}

.room-catalogue {
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
</style>
