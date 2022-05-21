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
                        <a href="">SMP Amerta</a>
                    </div>
                    <div class="nav-toggle">
                        <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                            <img src="icon/menu-right-wh.svg" alt=""></a>
                    </div>
                </div>
                <div class="nav" id="navbar-collapse">
                    <a href="index.html" class="navbar-list">Beranda</a>
                    <a href="menu_utama.html" class="navbar-list">Menu Utama</a>
                    <a href="daftar_foto.html" class="navbar-list">Foto Kegiatan</a>
                    <a href="daftar_tanaman.html" class="navbar-list">Info Tanaman</a>
                    <a href="tentang.html" class="navbar-list">Tentang</a>
                </div>
            </nav>
        </header>
        <div class="main-page">
            <div class="tentang">
                <h2>Identitas SMP Amerta</h2>
            </div>
            <ul>
                <li class="tentang-item">Nama Sekolah : SMP Amerta</li>
                <li class="tentang-item">Nomor Pokok Sekolah Nasional
                    : 69987585</li>
                <li class="tentang-item">Jenjang Pendidikan
                    : SMP</li>
                <li class="tentang-item">Status Sekolah
                    : Swasta</li>
                <li class="tentang-item">Alamat Sekolah :</li>
                Jl Cikelun Komplek Kuil Myogan-Ji RT 002/003
                <li class="">RT/RW
                    : 2 / 3</li>
                <li class="">Dusun
                    : Megamendung</li>
                <li class=""> Desa Kelurahan
                    : Megamendung</li>
                <li class=""> Kecamatan
                    : Kec. Megamendung</li>
                <li class="">Kabupaten
                    : Kab. Bogor</li>
                <li class="">Provinsi
                    : Prov. Jawa Barat</li>
                <li class="tentang-item">Kode Pos
                    : 16770</li>
                <li class="tentang-item">Lokasi Geografis
                    : Lintang -6 Bujur 106</li>
            </ul>
        </div>
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