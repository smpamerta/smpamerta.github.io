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
        <div class="tanaman-home-title">
            <h2>Glosarium Tanaman</h2>
        </div>
        <div class="tanaman-home">
            <div class="card-home">
                <div class="card-item-home">
                    <a href="page/damar.html">
                        <div class="img-card-home">
                            <img src="img/damar.jpg" alt="">
                        </div>
                    </a>
                    <div class="text-card">Pohon Damar</div>
                </div>
                <div class="card-item-home">
                    <a href="page/eboni.html">
                        <div class="img-card-home">
                            <img src="img/eboni.jpg" alt="">
                        </div>
                    </a>
                    <div class="text-card">Pohon Eboni</div>
                </div>
                <div class="card-item-home">
                    <a href="page/pinus.html">
                        <div class="img-card-home">
                            <img src="img/pinus.jpg" alt="">
                        </div>
                    </a>
                    <div class="text-card">Pohon Pinus</div>
                </div>
                <div class="card-item-home">
                    <a href="page/pinus.html">
                        <div class="img-card-home">
                            <img src="img/pinus.jpg" alt="">
                        </div>
                    </a>
                    <div class="text-card">Pohon Pinus</div>
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