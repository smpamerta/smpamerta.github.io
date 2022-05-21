<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../style2.css">
    <title>SMP Amerta</title>
</head>

<body>
    <div class="page">
        <header>
            <nav class="nav-page">
                <div class="navbar-menu" id="navbar-collapse-menu">
                    <div class="brand">
                        <a href="../daftar_tanaman.md"><img src="../icon/arrow back.svg" alt="" width="20px"></a>
                    </div>
                    <div class="nav-toggle">
                        <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                            <img src="../icon/menu-right-wh.svg" alt=""></a>
                    </div>
                </div>
                <div class="nav" id="navbar-collapse">
                    <a href="../index.md" class="navbar-list">Beranda</a>
                    <a href="../menu_utama.md" class="navbar-list">Menu Utama</a>
                    <a href="../daftar_foto.md" class="navbar-list">Foto Kegiatan</a>
                    <a href="../daftar_tanaman.md" class="navbar-list">Info Tanaman</a>
                    <a href="../tentang.md" class="navbar-list">Tentang</a>
                </div>
            </nav>
        </header>
        <div class="main-tanaman-detail">
            <div class="cover-img">
                <img src="../img/adiwiyati/merbau.jpg" alt="">
            </div>
            <div class="detail">
                <div class="detail-title">
                    <h2>Merbau</h2>
                </div>
                <div class="klasifikasi">
                    <div class="title-icon">
                        <img src="../icon/leaves.png" alt="">
                        <h3>Klasifikasi</h3>
                    </div>
                    <p> Kingdom : Plantae
                        Divisi : Magnoliophyta
                        Kelas : Magnoliopsida
                        Ordo : Fabales
                        Famili : Fabaceae
                        Genus : Intsia
                        Spesies : Intsia Bijuga </p>
                </div>
                <div class="klasifikasi">
                    <div class="title-icon">
                        <img src="../icon/logs.png" alt="">
                        <h3>Manfaat</h3>
                    </div>
                    <p>1. Bisa Dimanfaatkan Sebagai Kusen. Manfaat paling banyak yang dirasakan dari kayu merbau ini
                        adalah sering digunakan sebagai kusen seperti pintu, jendela dan lainnya. <br>
                        2. Lantai Parket. Pemilihan kayu ini sebagai bahan untuk lantai adalah karena karakteristiknya
                        yang khas. <br>
                        3. Obat Tradisional. Mungkin tak ada yang menyangka jika kayu ini pun bisa digunakan sebagai
                        bahan obat tradisional. Namun, bukan kayu yang digunakan melainkan bagian lain dari pohon merbau
                        yaitu minyak dari pohon serta daun pohon merbau yang berkhasiat.<br>
                        4. Tiang dan Bantalan Rumah. Bukan hanya sebagai bahan kusen, kayu jenis ini banyak digunakan
                        sebagai tiang atau bantalan rumah. Hal ini karena sifat pohon merbau yang keras dan awet
                        sehingga banyak orang yang percaya jika menggunakan jenis ini maka rumah pun akan bertahan lama.
                        <br>
                    </p>
                </div>
            </div>
        </div>
        <footer>
            <p class="center">WebApp Tanaman Sekolah v.1 &copy;smpamerta.2022</p>
            <div class="medsos-list">
                <div class="medsos">
                    <div class="medsos-item">
                        <img src="../icon/facebook.png" alt="">
                    </div>
                    <div class="medsos-item">
                        <a href="">SmkdanSmp Amerta</a>
                    </div>
                </div>
                <div class="medsos">
                    <div class="medsos-item">
                        <img src="../icon/gmail.png" alt="">
                    </div>
                    <div class="medsos-item">
                        <a href="">smpamerta@gmail.com</a>
                    </div>
                </div>
                <div class="medsos">
                    <div class="medsos-item">
                        <img src="../icon/telepone.png" alt="">
                    </div>
                    <div class="medsos-item">
                        <a href="">(0251)8298485</a>
                    </div>
                </div>
            </div>
        </footer>
    </div>
    </div>


    <script>
        function myFunction() {
            var x = document.getElementById("navbar-collapse");
            if (x.className === "nav") {
                x.className = " responsive";
            } else {
                x.className = "nav";
            }
            var x = document.getElementById("navbar-collapse-menu");
            if (x.className === "navbar-menu") {
                x.className = "responsive-menu";
            } else {
                x.className = "navbar-menu";
            }
        }
    </script>
</body>

</html>