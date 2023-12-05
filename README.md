# online-marketplace-for-handmade-crafts
#college project on Online Marketplace for Handmade Crafts using HTML and CSS.
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Handmade Craft Marketplace</title>
<style>
html{
  background-color: rgb(245, 236, 220);
}
header {
    background-color: #dba555;
    color: #fff;
    text-align: center;
    padding: 20px;
}

div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}
div.gallery img {
  width: 100%;
  height: 100%;
}
div.gallery:hover{
  width: 90%;
  height:auto;
  align-items: center;
  align-content: center;
}
div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
  margin:10px auto;
}

footer {
    background-color: #f4bf6f;
    color: #fff;
    text-align: center;
    padding: 10px;
}
form {
            max-width: 600px;
            margin-top: 2000px;
            margin-left: auto;
            margin-right: auto;
            margin-bottom: 100px;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="text"],
        input[type="number"],
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            background-color: #333;
            color: white;
            cursor: pointer;
        }
      
h3{
  text-align: center;
}

</style>



  <header>
    <h1>Welcome to the Handmade Craft Marketplace</h1>
    <p>Discover Unique Handcrafted Items</p>
</header>

<nav>
    <ul>
        <li><a href="#about">About Us</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section id="about">
    <h2>About Us</h2>
    <p>Welcome to our marketplace, where you can find a wide variety of beautiful, handcrafted items. 
        Our platform connects talented artisans with those who appreciate the art of handmade crafts.</p>
</section>
</head>
<body>
  <section id="products"></section>
<div class="responsive">
  <div class="gallery">
    <img src="decor.jpg" alt="Handmade Craft 1" >
            <h3>Lamp Home Decor</h3>
            <div class="desc">$15<br>
                This is home decoration piece. Durable and strong. In-built golden lightings.<br>
                Made in India. </div>
    <button>Add to Cart</button>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <img src="embroidary.jpg" alt="Handmade Craft 2">
            <h3>Heart Embroided Hankerchief</h3>
    <div class="desc">$6<br>Beautifully embroided, a masterpeice by Ms. Dhanaya from Chennai, India.</div>
    <button>Add to Cart</button>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="musical instruments.jpg" alt="Handmade Craft 2">
            <h3>Musical Instruments</h3>
    <div class="desc">$200<br>Amazingly built by Mr.Ramesh Santoshi. Ever-lasting musical instruments.</div>
    <button>Add to Cart</button>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="basket.jpg" alt="Handmade Craft 2">
            <h3>Basket</h3>
    <div class="desc">$90<br>Basket that can be used for keeping fruits or for errands and many more wonders.</div>
    <button>Add to Cart</button>
  </div>
</div>
<div class="responsive">
  <div class="gallery">
    <img src="handbag.jpg" alt="Handmade Craft 2">
            <h3>Slaying Bag</h3>
    <div class="desc">$15<br>Amazing handbag that can keep anything inside it.</div>
    <button>Add to Cart</button>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <img src="jewellery.jpg" alt="Handmade Craft 2">
            <h3>Jewellery</h3>
    <div class="desc">$450<br>Wonderful jewellery sets available.</div>
    <button>Add to Cart</button>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="flowercube.jpg" alt="Handmade Craft 2">
            <h3>Flower Cubes</h3>
    <div class="desc">$80<br>Elegant flower cubes for home decoration purposes.</div>
    <button>Add to Cart</button>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="dreamcatcher.jpg" alt="Handmade Craft 2">
            <h3>Halloween Dream Cathcer</h3>
    <div class="desc">$190<br>Happy Halloween. Buy these horror yet elegant Halloween Dream Catchers this Halloween.</div>
    <button>Add to Cart</button>
  </div>
</div>
<div class="responsive">
  <div class="gallery">
      <img src="cushions.jpg" alt="cushions">
      <h3>Cushion Set</h3>
    <div class="desc">$140<br>Cushion set for lobby</div>
    <button>Add to Cart</button>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
      <img src="Screenshot 2023-12-03 225308.png" alt="yak cloth">
      <h3>Yak Wool Scraf</h3>
    <div class="desc">$1122<br>Handmade Himalayan Yak Wool Scarf from Nepal - Light Beige</div>
    <button>Add to Cart</button>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
      <img src="Screenshot 2023-12-03 225645.png" alt="axe" >
      <h3>Steel Axe</h3>
    <div class="desc">$2000<br>Beautiful Damascus Steel Axe | Custom Handmade Damascus Steel Axe with Leather Sheath/ Birthday Gift/ Christmas Gift/ Anniversary Gift</div>
    <button>Add to Cart</button>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
      <img src="Screenshot 2023-12-03 225842.png" alt="kitty coaster">
      <h3>Kitty Coaster</h3>
    <div class="desc">DIY Coaster Punch Needle Kit Tufting Coaster  - Drink Coasters Punch Needle Embroidery Kit Christmas Gifts</div>
    <button>Add to Cart</button>
  </div>
</div>
</section>
<div>
<form>
  <h2>Checkout</h2>
  <label for="productName">Product Name:</label>
  <input type="text" id="productName" name="productName" required>

  <label for="quantity">Quantity:</label>
  <input type="number" id="quantity" name="quantity" min="1" required>

  <label for="creditCard">Credit Card Number:</label>
  <input type="text" id="creditCard" name="creditCard" required>

  <input type="submit" value="Place Order">
</form>
</div>
<section id="contact">
  <h2>Contact Us</h2>
  <p>If you have any questions or would like to get in touch with us, please email us at <a href="mailto:info@example.com">handmadecrafts@gmail.com</a>.</p>
</section>

<script scr="https://kit.fontawespme.com/ef9a692198.js" crossorigin="anonymous"></script>
</body>

<footer>
  <p>&copy; 2023 Handmade Craft Marketplace</p>
</footer>
</body>
</html>
