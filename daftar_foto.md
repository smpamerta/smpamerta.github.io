<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style2.css">
    <title>SMP Amerta</title>
</head>

<body>
    <div class="page">
        <header>
            <nav class="nav-page">
                <div class="navbar-menu" id="navbar-collapse-menu">
                    <div class="brand">
                        <a href="menu_utama.md">SMP Amerta</a>
                    </div>
                    <div class="nav-toggle">
                        <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                            <img src="icon/menu-right-wh.svg" alt=""></a>
                    </div>
                </div>
                <div class="nav" id="navbar-collapse">
                    <a href="index.md" class="navbar-list">Beranda</a>
                    <a href="menu_utama.md" class="navbar-list">Menu Utama</a>
                    <a href="daftar_foto.md" class="navbar-list">Foto Kegiatan</a>
                    <a href="daftar_tanaman.md" class="navbar-list">Info Tanaman</a>
                    <a href="tentang.md" class="navbar-list">Tentang</a>
                </div>
            </nav>
        </header>
        <div class="main-page">
            <div class="daftar-foto">
                <div class="foto-list">
                    <a href="page-foto/verifikasi.md" class="foto-item">
                        <img src="img/kegiatan/1.JPG" alt="">
                        <p>Kegiatan Verifikasi</p>
                    </a>
                    <a href="page-foto/penanaman.md" class="foto-item">
                        <img src="img/kegiatan/nanam.jpg" alt="">
                        <p>Penanaman Bibit</p>
                    </a>
                    <a href="page-foto/kegiatan.md" class="foto-item">
                        <img src="img/kegiatan/pangan.jpg" alt="">
                        <p>Kegiatan Adiwiyata</p>
                    </a>
                </div>
            </div>
        </div>
        <footer>
            <p class="center">WebApp Tanaman Sekolah v.1 &copy;smpamerta.2022</p>
            <div class="medsos-list">
                <div class="medsos">
                    <div class="medsos-item">
                        <img src="icon/facebook.png" alt="">
                    </div>
                    <div class="medsos-item">
                        <a href="">SmkdanSmp Amerta</a>
                    </div>
                </div>
                <div class="medsos">
                    <div class="medsos-item">
                        <img src="icon/gmail.png" alt="">
                    </div>
                    <div class="medsos-item">
                        <a href="">smpamerta@gmail.com</a>
                    </div>
                </div>
                <div class="medsos">
                    <div class="medsos-item">
                        <img src="icon/telepone.png" alt="">
                    </div>
                    <div class="medsos-item">
                        <a href="">(0251)8298485</a>
                    </div>
                </div>
            </div>
        </footer>
    </div>

    <!--  -->

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