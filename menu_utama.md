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
            <div class="gallery">
                <div class="title">
                    <h5>Foto Kegiatan</h5>
                    <a href="daftar_foto.md">
                        <h6>Lihat Semua>></h6>
                    </a>
                </div>
                <div class="photo">
                    <div class="photo-box photo1">
                        <a href="page-foto/verifikasi.md">
                            <img src="img/kegiatan/9.jpg" alt="">
                            <div class="text-box">
                                <h6>Verifikasi Adiwiyata Kab.Bogor</h6>
                            </div>
                        </a>
                    </div>
                    <div class="photo-box photo3">
                        <a href="page-foto/penanaman.md">
                            <img src="img/kegiatan/nanam.jpg" alt="">
                            <div class="text-box">
                                <h6>Penanaman bibit</h6>
                            </div>
                        </a>
                    </div>
                    <div class="photo-box photo2">
                        <a href="page-foto/kegiatan.md">
                            <img src="img/kegiatan/pangan.jpg" alt="">
                            <div class="text-box">
                                <h6>Kegiatan Adiwiyata</h6>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
            <div class="tanaman">
                <div class="title">
                    <h5>Tanaman Di Sekolah</h5>
                    <a href="daftar_tanaman.md">
                        <h6>Lihat Semua>></h6>
                    </a>
                </div>
                <div class="list-tanaman">
                    <div class="tanaman-box">
                        <a href="page-tanaman/jambu_jamaika.md">
                            <img src="img/adiwiyati/jambu jamaika.jpg" alt="">
                            <div class="text-box">
                                <h6>Jambu Jamaika</h6>
                            </div>
                        </a>
                    </div>
                    <div class="tanaman-box">
                        <a href="page-tanaman/merbau.md">
                            <img src="img/adiwiyati/merbau.jpg" alt="">
                            <div class="text-box">
                                <h6>Merbau</h6>
                            </div>
                        </a>
                    </div>
                    <div class="tanaman-box">
                        <a href="page-tanaman/kenari.md">
                            <img src="img/adiwiyati/kenari.jpg" alt="">
                            <div class="text-box">
                                <h6>Kenari</h6>
                            </div>
                        </a>
                    </div>
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
