<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Điện Máy Xanh </title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>🔌 Điện Máy Xanh </h1>
    <nav>
      <a href="#">Trang chủ</a>
      <a href="#">Sản phẩm</a>
      <a href="#">Giỏ hàng 🛒 (<span id="cart-count">0</span>)</a>
    </nav>
  </header>

  <main>
    <h2>Sản phẩm nổi bật</h2>
    <div class="product-list" id="product-list">
      <!-- Sản phẩm được hiển thị bằng JavaScript -->
    </div>
  </main>

  <script src="script.js"></script>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}
header {
  background-color: #0077cc;
  color: white;
  padding: 20px;
  text-align: center;
}
nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}
.product-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  padding: 20px;
}
.product {
  border: 1px solid #ccc;
  margin: 10px;
  padding: 15px;
  width: 200px;
  text-align: center;
}
.product img {
  width: 100%;
  height: auto;
}
button {
  background-color: #28a745;
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
}

