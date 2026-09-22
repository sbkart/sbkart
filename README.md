<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SBKART - Online Shopping</title>

<style>
*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

body{
    font-family:Arial,sans-serif;
    background:#f5f5f5;
    color:#222;
}

header{
    background:#111827;
    color:white;
    padding:15px;
    position:sticky;
    top:0;
    z-index:10;
}

.top{
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo{
    font-size:25px;
    font-weight:bold;
}

.cart{
    font-size:25px;
}

.search{
    margin-top:12px;
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    font-size:16px;
}

.banner{
    background:#2563eb;
    color:white;
    margin:15px;
    padding:25px 15px;
    border-radius:12px;
    text-align:center;
}

.banner h1{
    font-size:28px;
    margin-bottom:8px;
}

.categories{
    padding:10px 15px;
}

.categories h2,
.products h2{
    margin-bottom:12px;
}

.category-list{
    display:flex;
    gap:10px;
    overflow-x:auto;
}

.category{
    background:white;
    padding:12px 18px;
    border-radius:20px;
    white-space:nowrap;
    border:1px solid #ddd;
}

.products{
    padding:15px;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(2,1fr);
    gap:12px;
}

.product{
    background:white;
    border-radius:10px;
    padding:10px;
    box-shadow:0 2px 6px #ddd;
}

.product-img{
    height:130px;
    background:#eee;
    border-radius:8px;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:45px;
}

.product h3{
    margin-top:10px;
    font-size:16px;
}

.price{
    color:#16a34a;
    font-size:18px;
    font-weight:bold;
    margin:7px 0;
}

button{
    width:100%;
    padding:10px;
    border:none;
    border-radius:7px;
    background:#f97316;
    color:white;
    font-weight:bold;
}

footer{
    margin-top:25px;
    background:#111827;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <div class="top">
        <div class="logo">🛍️ SBKART</div>
        <div class="cart">🛒</div>
    </div>

    <input
        class="search"
        type="text"
        placeholder="Search products..."
    >
</header>

<section class="banner">
    <h1>Welcome to SBKART</h1>
    <p>All Products • Only UPI Payment</p>
</section>

<section class="categories">
    <h2>Categories</h2>

    <div class="category-list">
        <div class="category">📱 Electronics</div>
        <div class="category">👕 Fashion</div>
        <div class="category">🏠 Home</div>
        <div class="category">💄 Beauty</div>
        <div class="category">⚽ Sports</div>
    </div>
</section>

<section class="products">
    <h2>Popular Products</h2>

    <div class="product-grid">

        <div class="product">
            <div class="product-img">📱</div>
            <h3>Smart Phone</h3>
            <div class="price">₹9,999</div>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <div class="product-img">🎧</div>
            <h3>Wireless Earbuds</h3>
            <div class="price">₹999</div>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <div class="product-img">⌚</div>
            <h3>Smart Watch</h3>
            <div class="price">₹1,499</div>
            <button>Add to Cart</button>
        </div>

        <div class="product">
            <div class="product-img">👕</div>
            <h3>Men T-Shirt</h3>
            <div class="price">₹499</div>
            <button>Add to Cart</button>
        </div>

    </div>
</section>

<footer>
    <p>SBKART © 2026</p>
    <p>Only UPI Payment</p>
</footer>

</body>
</html>
