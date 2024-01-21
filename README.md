<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="tampilan.css">
    <title>iPhoneQu Store</title>
</head>


<body>
    <header>
        <img src="logoku.jpeg" alt="Logo" class="logo">
        <h1>iPhoneQu Store</h1>
        <nav>
            <ul>
                <li><a href="website_sederhana.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="sosmed.html">Social Media</a></li>
            </ul>
        </nav>
    </header>
    <script>
        // Fungsi untuk menampilkan pesan konfirmasi
        function beliProduk(Iphone) {
            alert("Anda telah membeli " + Iphone + ". Terima kasih!");
        }
    </script>

    <main>
        <section class="product-list">
            <h2>Daftar Produk:</h2>
            <ul>
                <li>
                    <img src="iphonese.jpg" alt="iPhone 1">
                    <p>iPhone SE</p>
                    <p class="price">Rp 8.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone SE')">Beli</button>
                </li>
                <li>
                    <img src="iphone12.jpg" alt="iPhone 2">
                    <p>iPhone 12</p>
                    <p class="price">Rp 11.500.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 12')">Beli</button>
                </li>
                <li>
                    <img src="iphone12pro.jpg" alt="iPhone 3">
                    <p>iPhone 12 Pro</p>
                    <p class="price">Rp 13.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 12 Pro')">Beli</button>
                </li>
                <li>
                    <img src="iphone13.jpg" alt="iPhone 4">
                    <p>iPhone 13</p>
                    <p class="price">Rp 14.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 13')">Beli</button>
                </li>
                <li>
                    <img src="iphone13pro.jpg" alt="iPhone 4">
                    <p>iPhone 13 Pro</p>
                    <p class="price">Rp 15.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 13 Pro')">Beli</button>
                </li>
                <li>
                    <img src="iphone14.jpg" alt="iPhone 5">
                    <p>iPhone 14</p>
                    <p class="price">Rp 17.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 14')">Beli</button>
                </li>
                <li>
                    <img src="iphone14pro.jpg" alt="iPhone 6">
                    <p>iPhone 14 Pro</p>
                    <p class="price">Rp 18.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 14 Pro')">Beli</button>
                </li>
                <li>
                    <img src="iphone15.jpg" alt="iPhone 7">
                    <p>iPhone 15</p>
                    <p class="price">Rp 20.000.000</p>
                    <button class="buy-button" onclick="beliProduk('iPhone 15')">Beli</button>
                </li>
                
            </ul>
            

    </main>

    <footer>
        <p>&copy; 2024 iPhoneQu Store. Hak Cipta Dilindungi.</p>
    </footer>
</body>

</html>

        </section>
    </main>
</body>

</html>
