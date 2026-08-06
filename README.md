<!-- Ex.No:03 Design a Web Page using HTML and CSS -->
<!-- Register No: URK24CS1092 -->
<!-- Theme: Online Food Delivery -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>QuickBite - Online Food Delivery</title>
<style>

    /* ===== General Page Setup ===== */
    body {
        font-family: georgia, garamond, serif;
        background-color: #fff8f0;
        margin: 0;
        padding: 0;
    }

    /* ===== Header ===== */
    header {
        background-color: #ff5722;
        background-image: url("https://www.transparenttextures.com/patterns/food.png");
        background-repeat: no-repeat;
        padding-top: 15px;
        padding-bottom: 15px;
        padding-left: 20px;
        padding-right: 20px;
        text-align: center;
    }

    header h1 {
        color: white;
        letter-spacing: 5px;
        text-shadow: 4px 4px 8px blue;
        font-weight: bolder;
        font-size: xx-large;
        margin-top: 10px;
        margin-bottom: 5px;
    }

    header p {
        color: #fff3e0;
        font-style: italic;
        font-size: medium;
        text-decoration: underline;
    }

    /* ===== Navigation Links ===== */
    nav {
        background-color: #2e2e2e;
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 10px;
        padding-bottom: 10px;
    }

    nav a {
        display: inline-block;
        color: white;
        margin-left: 15px;
        margin-right: 15px;
        font-size: 18px;
        font-weight: bold;
        text-decoration: none;
        padding-top: 6px;
        padding-bottom: 6px;
        padding-left: 8px;
        padding-right: 8px;
    }

    nav a:link { background-color: transparent; }
    nav a:visited { color: #dddddd; }
    nav a:hover { background-color: #ff5722; color: white; }
    nav a:active { background-color: hotpink; }

    /* ===== Menu Section ===== */
    .menu-section {
        margin-top: 40px;
        margin-bottom: 40px;
        margin-left: 80px;
        margin-right: 80px;
    }

    .menu-section h2 {
        color: #d84315;
        text-align: center;
        font-size: x-large;
        letter-spacing: 2px;
        margin-bottom: 30px;
    }

    /* Multicolumn layout, kept perfectly aligned with flexbox */
    .card-row {
        display: flex;
        justify-content: space-between;
        align-items: stretch;
    }

    .food-card {
        background-color: lightblue;
        display: flex;
        flex-direction: column;
        justify-content: center;
        box-sizing: border-box;
        width: 30%;
        height: 220px;
        padding: 15px;
        margin-bottom: 20px;
        border-radius: 8px;
        text-align: center;
    }

    .food-card h3 {
        font-family: garamond, serif;
        font-weight: 600;
        color: #333;
        margin-top: 0;
        margin-bottom: 10px;
    }

    .food-card p {
        font-size: small;
        color: #444;
        margin: 0;
    }

    /* ===== Offers List ===== */
    .offers {
        margin-left: 100px;
        margin-right: 100px;
        margin-bottom: 40px;
        background-color: #ffe0b2;
        padding-top: 20px;
        padding-bottom: 20px;
        padding-left: 30px;
        padding-right: 30px;
    }

    .offers h2 {
        text-align: left;
        text-decoration: overline;
        color: #bf360c;
    }

    .offers ul {
        list-style-type: circle;
    }

    .offers li {
        font-size: 16px;
        color: #333;
        margin-bottom: 8px;
    }

    /* ===== Footer ===== */
    footer {
        background-color: #2e2e2e;
        color: white;
        text-align: center;
        padding-top: 15px;
        padding-bottom: 15px;
        font-size: small;
    }

</style>
</head>
<body>

    <header>
        <h1>QuickBite</h1>
        <p>Delicious food, delivered to your doorstep</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#offers">Offers</a>
        <a href="#track">Track Order</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="menu-section" id="menu">
        <h2>Our Popular Dishes</h2>

        <div class="card-row">
            <div class="food-card">
                <h3>Margherita Pizza</h3>
                <p>Classic cheese pizza topped with fresh basil and tomato sauce.</p>
            </div>

            <div class="food-card">
                <h3>Chicken Biryani</h3>
                <p>Fragrant basmati rice cooked with spiced chicken and herbs.</p>
            </div>

            <div class="food-card">
                <h3>Veg Burger</h3>
                <p>Crispy patty with lettuce, cheese, and special sauce.</p>
            </div>
        </div>

    </section>

    <section class="offers" id="offers">
        <h2>Today's Offers</h2>
        <ul>
            <li>Flat 50% off on your first order</li>
            <li>Free delivery on orders above &#8377;299</li>
            <li>Buy 1 Get 1 on selected combos</li>
            <li>Extra 10% cashback with UPI payment</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2026 QuickBite Food Delivery. All rights reserved.</p>
    </footer>

</body>
</html>
