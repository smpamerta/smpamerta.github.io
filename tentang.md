<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="splide.min.css">
    <title>Document</title>
</head>

<body>
    <div class="navbar">
        <div class="topnav">
            <div class="nav-toggle">
                <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                    <img src="icon/menu.svg" alt=""></a>
            </div>
            <div class="nav-brand">
                <a href="#">SMP Amerta</a>
            </div>
        </div>
        <div class="nav" id="navbar-collapse">
            <div class="nav-item">
                <a href="index.html">Home</a>
            </div>
            <div class="nav-item">
                <a href="tanaman.html">Tanaman</a>
            </div>
            <div class="nav-item">
                <a href="tentang.html">Tentang</a>
            </div>
        </div>
    </div>
    <div class="content">
        <div class="welcome-tentang">
            <h2>Identitas SMP Amerta</h2>
        </div>
        <ul>
            <li class="identitas-list">Nama Sekolah : SMP Amerta</li>
            <li class="identitas-list">Nomor Pokok Sekolah Nasional
                : 69987585</li>
            <li class="identitas-list">Jenjang Pendidikan
                : SMP</li>
            <li class="identitas-list">Status Sekolah
                : Swasta</li>
            <li class="identitas-list">Alamat Sekolah :</li>
            Jl Cikelun Komplek Kuil Myogan-Ji RT 002/003
            <li class="identitas-list"></li>RT/RW
            : 2 / 3
            <li class="identitas-list"></li>Dosun
            : Megamendung
            <li class="identitas-list"> Desa Kelurahan
                : Megamendung
            <li class="identitas-list"> Kecamatan
                : Kec. Megamendung
            <li class="identitas-list"></li>Kabupaten
            : Kab. Bogor
            <li class="identitas-list"></li>Provinsi
            : Prov. Jawa Barat
            <li class="identitas-list"></li>Kode Pos
            : 16770
            <li class="identitas-list">Lokasi Geografis
                : Lintang -6 Bujur 106</li>
        </ul>
    </div>
    <footer>
        SMP Amerta &copy; 2022
    </footer>

    <script>
        function myFunction() {
            var x = document.getElementById("navbar-collapse");
            if (x.className === "nav") {
                x.className = " responsive";
            } else {
                x.className = "nav";
            }
        }
    </script>
    <script src="splide.js"></script>

</body>

</html>