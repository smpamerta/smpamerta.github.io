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
            <div class="barcode">
                <h3>Daftar Barcode</h3>
                <div class="barcode-list">
                    <div class="barcode-item">
                        <img src="barcode/example.jpg" alt="">
                        <p>example barcode</p>
                    </div>
                    <div class="barcode-item">
                        <img src="barcode/example.jpg" alt="">
                        <p>example barcode</p>
                    </div>
                </div>
            </div>
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