<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="splide.min.css">
    <title>Document</title>
</head>

<body>
    <div class="navbar">
        <div class="topnav">
            <div class="nav-toggle">
                <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                    <img src="../icon/menu.svg" alt=""></a>
            </div>
            <div class="nav-brand">
                <a href="#">SMP Amerta</a>
            </div>
        </div>
        <div class="nav" id="navbar-collapse">
            <div class="nav-item">
                <a href="#">Home</a>
            </div>
            <div class="nav-item">
                <a href="#">Tanaman</a>
            </div>
            <div class="nav-item">
                <a href="#">Tentang</a>
            </div>
        </div>
    </div>
    <div class="content-page">
        <div class="page-tanaman">
            <div class="tanaman-title">
                <h2>Pohon Damar</h2>
            </div>
            <div class="tanaman-nav">
                <a href="#" class="item-nav">
                    <img src="../icon/tree.png" alt="">
                    <p>Ciri dan Karakteristik</p>
                </a>
                <a href="#" class="item-nav">
                    <img src="../icon/logs.png" alt="">
                    <p>Pemanfaatan Pohon</p>
                </a>
                <a href="#" class="item-nav">
                    <img src="../icon/leaves.png" alt="">
                    <p>Klasifikasi Ilmiah</p>
                </a>
            </div>
            <div class="tanaman-img">
                <img src="../img/damar.jpg" alt="">
            </div>
            <div class="tanaman-klasifikasi">
                <div class="ciri" id="tCiri">
                    <h3>Ciri dan Karakteristik </h3>
                    <p style="text-indent: 50px;">Damar merupakan tumbuhan asli Indonesia. Daerah sebarannya meliputi
                        pulau Sulawesi, kepulauan
                        Maluku, dan kepulauan di Filipina. Namun kini, pohon damar telah dibudidayakan di
                        perkebunan-perkebunan di pulau Jawa. Tumbuh di hutan hujan tropis dataran rendah hingga
                        ketinggian 1.200 meter di atas permukaan laut.</p>

                    <p style="text-indent: 50px;">Pohon damar (Agathis dammara) berukuran besar dan tingginya bisa
                        mencapai 65 meter. Batangnya
                        silindris dan lurus dengan diameter mencapai 1,5 meter. Kulit batang berwarna abu-abu muda
                        hingga coklat kemerahan. Kulit mengelupas dalam keping-keping yang tidak beraturan dan biasanya
                        bopeng karena resin.</p>

                    <p style="text-indent: 50px;">Daun berbentuk jorong (bulat memanjang) dengan panjang 6 – 8 cm
                        dan lebar 2 – 3 cm. Bagian
                        pangkal daun membaji sedangkan ujungnya runcing. Tulang daun sejajar dan banyak. Bunga jantan
                        dan betina berada pada tandan yang berbeda, pada pohon yang sama (berumah satu).</p>

                    <p style="text-indent: 50px;">Meskipun tidak termasuk tanaman langka, namun pohon damar (Agathis
                        dammara) di habitat aslinya
                        telah mengalami populasi hingga 30% dalam 75 tahun terakhir. Oleh karena itu Daftar Merah
                        International Union for Conservation of Nature (IUCN Redlist) memasukkannya dalam spesies
                        Vulnerable (Rentan).</p>
                    <div class="br-btm"></div>
                </div>
                <div class="manfaat" id="tManfaat">
                    <h3>Pemanfaatan Pohon</h3>
                    <p style="text-indent: 50px;">Manfaat utama damar adalah diambil getahnya untuk dioleh menjadi kopal
                        (manila copal). Getah damar keluar dari anavar kulit atau kayu damar yang dilukai. Getah yang
                        keluar akan membeku dan mengeras setelah beberap hari. Getah damar yang mengeras nilah yang
                        kemudian dinamai kopal.</p>

                    <p style="text-indent: 50px;">Kopal ini mengandung asam-asam resinol, resin, dan minyak atsiri.
                        Kopal merupakan bahan dasar bagi cairan pelapis kertas supaya tinta tidak menyebar. Selain itu
                        kopal dimanfaatkan untuk campuran lak dan vernis, perekat pada penambal gigi, dan perekat
                        plester.</p>

                    <p style="text-indent: 50px;">Pohon damar juga bisa dijadikan pohon penghijauan dan peneduh.
                        Sedangkan kayunya, meskipun kurrang kuat dan awet, kerap diperdagangkan sebagai bahan bangunan
                        dengan nama ‘kayu agatis’.</p>

                    <div class="br-btm"></div>
                </div>
                <div class="klasifikasi" id="tKlasifikasi">
                    <h3>Klasifikasi Ilmiah</h3>
                    <p>Kerajaan : Plantae. Filum : Tracheophyta. Kelas : Pinopsida. Ordo :
                        Pinales. Famili : Araucariaceae. Genus : Agathis.</p>
                    <br>
                    <p>Spesies : Agathis dammara.</p>
                </div>
            </div>
        </div>

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