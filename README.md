<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Toko Cupang Keren</title>

<style>
body {
    font-family: Arial;
    margin: 0;
    min-height: 100vh;

    background: radial-gradient(circle at 20% 30%, rgba(0,255,150,0.3), transparent 40%),
                radial-gradient(circle at 80% 70%, rgba(0,200,100,0.3), transparent 40%),
                linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    background-attachment: fixed;
    color: white;
} /* ===== PRODUK ===== */
.produk {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

/* CARD */
.card {
    background: rgba(255,255,255,0.1);
    padding: 15px;
    border-radius: 15px;
}

/* RATING */
.rating {
    color: gold;
}

/* ULASAN */
.ulasan {
    font-size: 13px;
}
/* HEADER */
header {
    background: rgba(0,0,0,0.6);
    backdrop-filter: blur(10px);
    text-align: center;
    padding: 20px;
}

/* NAV */
nav {
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #00ff95;
}

/* CONTAINER */
.container { 
    padding: 20px;
}


/* PRODUK */
.produk {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
}

/* CARD */
.card {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    padding: 15px;
    border-radius: 15px;
    width: 250px;
    text-align: center;
    transition: 0.4s;
    box-shadow: 0 0 10px rgba(0,255,150,0.2);
}

.card:hover {
    transform: translateY(-10px) scale(1.03);
    box-shadow: 0 0 20px rgba(0,255,150,0.6);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
}

/* BUTTON */
.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px;
    background: linear-gradient(45deg, #00ff95, #00c864);
    color: black;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: 0.3s;
}

.btn:hover {
    background: white;
    color: black;
}

/* KONTAK */
.kontak {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
}

.box {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(10px);
    padding: 15px;
    border-radius: 10px;
    flex: 1;
}

/* FORM */
input, textarea, select {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border-radius: 5px;
    border: none;
}

button {
    background: #00ff95;
    color: black;
    padding: 10px;
    border: none;
    width: 100%;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
}

button:hover {
    background: white;
}

/* FOOTER */
footer {
    background: rgba(0,0,0,0.7);
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}

/* ANIMASI MASUK */
.card {
    animation: fadeUp 1s ease;
}

@keyframes fadeUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
</style>
</head>

<body>

<header>
    <h1>🐟 CUPANG & HIAS</h1>
    <p>Jual Ikan Cupang Berkualitas Harga Terjangkau</p>
</header>

<nav>
    <a href="#">Beranda</a>
    <a href="#produk">Produk</a>
    <a href="#kontak">Kontak</a>
</nav>

<div class="container">
    

<h2 id="produk">Produk Cupang</h2>

<div class="produk">
<div class="produk">
    <div class="card">
        <img src="https://operational-magenta-ysxzubp41t.edgeone.app/IMG-20260406-WA0041.jpg"
     style="width:100%; height:200px; object-fit:cover;">

        <h3>Cupang Hias Clasik</h3>

        <div class="rating">⭐⭐⭐⭐⭐ 4.9</div>

        <p class="ulasan">
            "indah dan menawan!"
        </p>

        <p><b>Rp 25.000</b></p>
    </div>

</div>
<div class="card">
        <img src="https://operational-magenta-ysxzubp41t.edgeone.app/IMG-20260406-WA0041.jpg"
     style="width:100%; height:200px; object-fit:cover;">


        <h3>Cupang Hias Clasik</h3>

        <div class="rating">⭐⭐⭐⭐⭐ 4.9</div>

        <p class="ulasan">
            "ganas dan berkualitas!"
        </p>
        <p><b>Rp 25.000</b></p>
</div>



</div>
<h2 id="kontak">Kontak Kami</h2>
<div class="kontak">
<div class="box">
    <h3>WhatsApp</h3>
    <a class="btn" href="https://wa.me/6283177094560">Chat WA</a>

    <h3>Email</h3>
    <p>syahdewadewa879@gmail.com</p>

    <h3>Instagram</h3>
    <p>SMART FISH HIAS</p>
</div>

<div class="box">
    <h3>Lokasi</h3>
    <p>Yogyakarta</p>

    <iframe 
  src="https://www.google.com/maps?q=KOLAM+LELE+SMART+FISH,+Jl.+Tutul+2,+Nologaten,+Depok,+Sleman,+Yogyakarta&output=embed"
  width="100%" 
  height="400" 
  style="border:0;" 
  allowfullscreen="" 
  loading="lazy">
</iframe>

</div>

<form>
<h2>Form Pemesanan</h2>

<input type="text" placeholder="Nama Lengkap" required>
<input type="tel" placeholder="No WhatsApp" required>
<input type="text" placeholder="Alamat" required>

<select required>
<option>Pilih Jenis</option>
<option>Cupang Hias</option>
<option>Cupang Aduan</option>
</select>

<input type="number" placeholder="Jumlah" min="1">

<textarea placeholder="Catatan"></textarea>

<button>Kirim Pesanan</button>
</form>

</div>

<footer>
<p>© 2026 Toko Cupang</p>
</footer>

</body>
</html>
