<!DOCTYPE html>
<html>
<head>
<title>Amai Bakery</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body,h1,h5 {font-family: "Raleway", sans-serif}
body, html {height: 100%}
.bgimg {
  background-image: url('/IMG_20240325_120338_998.jpg');
  min-height: 100%;
  background-position: center;
  background-size: cover;
}
</style>
</head>
<body>

<div class="bgimg w3-display-container w3-text-black">
  <div class="w3-display-middle w3-jumbo">
    <p>Welcome To Amai Bakery</p>
  </div>
  <div class="w3-display-topleft w3-container w3-xlarge">
    <p><button onclick="document.getElementById('Menu').style.display='block'" class="w3-button w3-non-white">三 Menu</button></p>
    <p><button onclick="document.getElementById('Order').style.display='block'" class="w3-button w3-non-black">三 Order</button></p>
  </div>
  <div class="w3-display-bottomleft w3-container">
    <p class="w3-xlarge">Open : Monday --> Sunday
     | Started: 7AM - 5PM ​</p>
    <p class="w3-large">ទីតាំង ៖ សង្កាត់ទឹកល្អក់ទី ៣  ,  ខណ្ឌ ទួលគោក  ,  រាជធានីភ្នំពេញ.</p>
    <p class="w3-large">Phone Number : 0xx xxx </p>
    <p>Design by <a href="Ann" target="_blank">Ann</a></p>
  </div>
</div>

<!-- Menu Modal -->
<div id="Menu" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black w3-display-container">
      <span onclick="document.getElementById('Menu').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>CapCakes</h1>
    </div>
    <div class="w3-container">
      <h5>Tomato <b>= $2.50</b></h5>

      <h5>Chicken Salad <b>$3.50</b></h5>

      <h5>Bread and Butter <b>$1.00</b></h5>

    </div>
    <div class="w3-container w3-black">
      <h1>Main Courses</h1>
    </div>
    <div class="w3-container">

      <h5>Grilled Fish and Potatoes <b>$8.50</b></h5>

      <h5>Italian Pizza <b>$5.50</b></h5>

      <h5>Veggie Pasta <b>$4.00</b></h5>

      <h5>Chicken and Potatoes <b>$6.50</b></h5>

      <h5>Deluxe Burger <b>$5.00</b></h5>

    </div>
    <div class="w3-container w3-black">
      <h1>Desserts</h1>
    </div>
    <div class="w3-container">
      <h5>Fruit Salad <b>$2.50</b></h5>

      <h5>Ice cream <b>$2.00</b></h5>

      <h5>Chocolate Cake <b>$4.00</b></h5>

      <h5>Cheese <b>$5.50</b></h5>
      
    </div>
  </div>
</div>

<!-- Contact Modal -->
<div id="Order" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-red">
      <span onclick="document.getElementById('Order').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Order</h1>
    </div>
    <div class="w3-container">
      <p>Reserve a table, ask for today's special or just send us a message:</p>
      <form action="https://t.me/AnnSRret" target="_blank">
        <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many Order" required name="Total"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
        <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Write your CapCakes " required name="Text"></p>
        <p class="w3-large"># Screenshort your Oder and then click { Order Now } #</p>
        <p class="w3-large">-------------Send Your Order to Telegram-------------</p>
        
        <p><button class="w3-button" type="submit">Order Now</button></p>
      </form>
    </div>
  </div>
</div>

</body>
</html>
