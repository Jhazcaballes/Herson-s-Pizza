# Herson-s-Pizza
Herson's Pizza &amp; Pasta welcome page features the restaurant's menu, about us section, and contact details. The design includes smooth scrolling, a background image, and sections for best-selling pizzas, new creations, pastas, and contact info. It’s mobile-friendly and encourages exploration and interaction.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome Page</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #f4f4f4;
      color: white;
      line-height: 1.6;
      padding: 10px;
      background-image: url(https://pointos.com/wp-content/uploads/2017/10/blur-background-of-pub-restaurant-with-wood-table-628137314_2125x1416.jpeg);
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }

    header,
    footer {
      background-color: #1E1E1E;
      color: white;
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-radius: 7px;
    }

    main {
      text-align: center;
    }

    .restaurant {
      text-align: center;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
    }

    .menu {
      text-align: center;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
      gap: 10%;
    }

    .bigtitle {
      font-size: 100px;
      font-family: Impact, sans-serif;
      color: white;
    }

    hr {
      border: none;
      height: 2px;
      background-color: grey;
      margin: 20px 0;
    }

    img {
      border-radius: 10px;
    }

    button {
      background-color: #1A4734;
      color: white;
      padding: 10px 20px;
      font-size: 1rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }

    button:hover {
      background-color: #418B24;
    }

    .company-name {
      margin: 0;
      font-size: 24px;
      font-weight: bold;
      color: white;
    }

    .button-container {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .Location {
      text-align: center;
    }

    .search {
      padding: 8px;
      border-radius: 5px;
      border: none;
      font-size: 1rem;
    }

    .Contact {
      background-color: aquamarine;
      padding: 40px;
    }

    #contact,
    .text {
      text-align: left;
    }

    #section1 {
      background-color: #870903;
      padding: 20px;
    }

    #section2 {
      background-color: #1E1E1E;
      padding: 20px;
    }

    #section3 {
      background-color: #870903;
      padding: 20px;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <header class="header-container">
    <img src="Logo.png" alt="Company Logo" width="100" height="100">
    <div class="button-container">
      <a href="#section2"><button>Menu</button></a>
      <a href="#section1"><button>Home</button></a>
      <button>Our Place</button>
      <a href="#section3"><button>Contact</button></a>
      <input class="search" type="text" placeholder="Type here.." />
    </div>
  </header>

  <p class="Location">Lower Jasaan Quezon Street, Zone 4, Riverside Misamis Oriental</p>

  <main>
    <h1 class="bigtitle">Herson's <br>Pizza & Pasta</h1>
    <p>Monday - Friday: 9:00 AM - 6:00 PM (GMT)</p>
    <button id="changeColorButton">See the menu!</button>
    <hr>

    <div id="section1">
      <h1 class="text">About us!!</h1>
      <div class="restaurant">
        <div>
          <h4>Customers</h4>
          <img src="Customer.jpg" alt="Customers enjoying pizza" width="300" height="400">
        </div>
        <div>
          <h4>Villa Branch</h4>
          <img src="Branch.jpg" alt="People enjoying pizza at the branch" width="300" height="400">
        </div>
        <div>
          <h4>Orders</h4>
          <img src="Order.jpg" alt="Pizza orders being served" width="300" height="400">
        </div>
      </div>
      <p>Herson's Pizza and Pasta is a cozy, family-friendly restaurant known for its delicious, freshly made pizzas and homemade pastas. With a menu featuring classic Italian favorites like margherita pizza, spaghetti bolognese, and creamy fettuccine alfredo, Herson’s offers a warm, welcoming atmosphere perfect for casual dining. Each dish is crafted with high-quality ingredients and a passion for authentic flavors, ensuring every bite is a delightful experience. Whether you're craving a slice of pizza or a hearty pasta dish, Herson’s promises to satisfy your culinary cravings.</p>
    </div>

    <hr>

    <div id="section2">
      <h1 class="text">Menu</h1>
      <div class="menu">
        <div class="text">
          <h2>Best-Selling Customer Favorites</h2>
          <ul>
            <li>Pepperoni Pizza -- 250</li>
            <li>Hawaiian Pizza -- 250</li>
            <li>Ham and Cheese -- 250</li>
            <li>Super Supreme Pizza -- 299</li>
          </ul>
        </div>
        <div>
          <img src="Pizza.jpg" alt="Pepperoni Pizza" width="400" height="500">
        </div>
      </div>

      <div class="menu">
        <div>
          <img src="Pizza2.jpg" alt="Hawaiian Pizza" width="400" height="500">
        </div>
        <div class="text">
          <h2>NEW PIZZA CREATIONS</h2>
          <ul>
            <li>BBQ Chicken Pizza -- 270</li>
            <li>Veggie Supreme -- 230</li>
            <li>Spicy Buffalo Pizza -- 280</li>
            <li>Seafood Delight -- 320</li>
          </ul>
        </div>
      </div>

      <div class="menu">
        <div class="text">
          <h2>PASTA</h2>
          <ul>
            <li>Carbonara -- 330</li>
            <li>Red Pasta -- 350</li>
            <li>Lasagna -- 450</li>
            <li>Spaghetti -- 220</li>
          </ul>
        </div>
        <div>
          <img src="Pasta.jpg" alt="Drinks" width="400" height="500">
        </div>
      </div>

      <p>Herson's Pizza and Pasta offers a cozy, family-friendly atmosphere with a menu full of delicious, freshly made pizzas and homemade pastas. Enjoy best-sellers like the classic Margherita pizza and savory Spaghetti Bolognese, or indulge in creamy Fettuccine Alfredo. Whether you're craving a slice of pizza or a hearty pasta dish, Herson’s serves authentic flavors with high-quality ingredients, making it the perfect spot for a satisfying meal.</p>
    </div>

    <hr>

    <div id="section3">
      <h1 class="text">Contact Us</h1>
      <div class="restaurant">
        <div class="text">
          <h3>Get in Touch</h3>
          <p>If you have questions, feedback, or want to make a reservation, feel free to reach out!</p>
          <p><strong>Address:</strong> Lower Jasaan Quezon Street, Zone 4, Riverside Misamis Oriental</p>
          <p><strong>Phone:</strong> +63 997 751 0747</p>
          <p><strong>Email:</strong> <a href="mailto:contact@hersonspizza.com" style="color: white;">Caballesjhazzen7@gmail.com</a></p>
        </div>

        <div class="text">
          <h3>Connect with Us</h3>
          <p>Stay updated on our latest promotions, events, and more by following us on social media!</p>
          <ul style="list-style: none; padding-left: 0;">
            <li><a href="https://www.instagram.com" target="_blank" style="color: white;">Instagram: @HersonsPizzaPasta</a></li>
            <li><a href="https://www.facebook.com/profile.php?id=100080307767384" target="_blank" style="color: white;">Facebook: Herson's Pizza & Pasta</a></li>
            <li><a href="https://www.twitter.com" target="_blank" style="color: white;">Twitter: @HersonsPizza</a></li>
          </ul>
        </div>

        <div class="text">
          <h3>Opening Hours</h3>
          <p><strong>Monday -- Friday:</strong><br> 9:00 AM -- 6:00 PM (GMT)</p>
          <p><strong>Saturday -- Sunday:</strong><br> Closed</p>
        </div>
      </div>
    </div>
    <hr>
  </main>

  <footer>
    <h3>Phone: +63 997 751 0747 <br />Email: Caballesjhazzen7@gmail.com<br>Address:Lower Jasaan Quezon Street, Zone 4, Riverside Misamis Oriental</h3>
    <img src="Logo.png" alt="Company Logo" width="100" height="100">
  </footer>

  <script src="script.js"></script>
</body>
</html>
