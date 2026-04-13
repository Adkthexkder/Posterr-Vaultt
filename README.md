# Posterr-Vault<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Editales Posters</title>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #ffffff;
  color: #111;
}

header {
  text-align: center;
  padding: 40px 20px;
}

h1 {
  font-size: 2.5rem;
  letter-spacing: 2px;
}

.tagline {
  color: #777;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  padding: 20px;
}

.card {
  border: 1px solid #eee;
  padding: 10px;
  text-align: center;
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.03);
}

.card img {
  width: 100%;
  height: auto;
}

.price {
  font-weight: bold;
}

button {
  padding: 10px;
  border: none;
  background: black;
  color: white;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 30px;
  color: #777;
}
</style>
</head>

<body>

<header>
  <h1>Editales Posters</h1>
  <p class="tagline">Minimal posters for modern minds</p>
</header>

<section class="gallery">

  <div class="card">
    <img src="poster1.jpg" alt="Poster">
    <p>Abstract Poster</p>
    <p class="price">₹199</p>
    <button onclick="order()">Order Now</button>
  </div>

  <div class="card">
    <img src="poster2.jpg" alt="Poster">
    <p>Dark Aesthetic</p>
    <p class="price">₹249</p>
    <button onclick="order()">Order Now</button>
  </div>

</section>

<footer>
  <p>DM on Instagram or WhatsApp to order</p>
</footer>

<script>
function order() {
  window.location.href = "https://wa.me/91YOURNUMBER";
}
</script>

</body>
</html>
