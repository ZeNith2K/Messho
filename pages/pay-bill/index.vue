<template>
  <div class="content">
    <div class="pay-bill-heading">
      <h1>Pay your Bills</h1>
    </div>
    <div class="bills-container">
      <div class="lodging">
        <h2>Lodging Bills</h2>
        <div class="bill">
          <div class="fields">
            <p>Room Rent</p>
            <p>Due Amount</p>
          </div>
          <div class="seperator">
            <p>:</p>
            <p>:</p>
          </div>
          <div class="details">
            <p>4300</p>
            <p>8600</p>
          </div>
        </div>
        <button>Pay</button>
      </div>
      <div class="fooding">
        <h2>Fooding Bills</h2>
        <div class="bill">
          <div class="fields">
            <p>Food Expenses</p>
            <p>Due Amount</p>
          </div>
          <div class="seperator">
            <p>:</p>
            <p>:</p>
          </div>
          <div class="details">
            <p>4300</p>
            <p>8600</p>
          </div>
        </div>
        <button>Pay</button>
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

.content{
  padding: 32px;
}

.pay-bill-heading{
  margin: auto;
  margin-bottom: 100px;
  padding: 16px;
  background-color: #1a192c;
  width: max-content;
  border: 3px solid #e03375;
  border-radius: 12px;
}

.pay-bill-heading h1{
  font-size: 1.8rem;
  font-family: "Montserrat", sans-serif;
  color: #f8edeb;
  font-weight: 500;
}

.bills-container{
  display: flex;
  margin: 32px 0;
  justify-content: space-around;
  align-content: center;
}

.lodging{
  width: 25vw;
  background: #35547c;
  text-align: center;
  padding: 32px 0;
  border-top: 4px solid #ee939b;
}

.lodging h2{
  font-family: "Montserrat",sans-serif;
  color: #1a192c;
  font-size: 1.7rem;
}

.fooding{
  padding: 32px 0;
  width: 25vw;
  background: #35547c;
  text-align: center;
  border-top: 4px solid  #ee939b;
}

.fooding h2{
  font-family: "Montserrat",sans-serif;
  color: #1a192c;
  font-size: 1.7rem;
}

.bill{
  display: flex;
  padding: 16px;
  justify-content: space-around;
  align-items: center;
  margin: 50px 0;
}

.fields{
  font-family: "Poppins",sans-serif;
  font-size: 1.2rem;
  color: #f6f6f6;
}

.seperator{
  font-family: "Poppins",sans-serif;
  font-size: 1.2rem;
  color: #f6f6f6;
}

.details{
  font-family: "Poppins",sans-serif;
  font-size: 1.2rem;
  color: #f6f6f6;
}

button{
  font-size: 1.3rem;
  font-family: "Poppins",sans-serif;
  background: #dd6847;
  color: whitesmoke;
  border: 2px solid whitesmoke;
  border-radius: 8px;
  padding: 2px;
  width: 100px;
}
</style>
