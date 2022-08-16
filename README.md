<!DOCTYPE html>
<html lang="pl">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProGamers</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/6fd82e5ea7.js" crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="./css/main.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>

<body data-bs-spy="scroll" data-bs-target="#navbar">

    <nav id="navbar" class="navbar navbar-expand-lg position-fixed top-0 w-100 py-3">
        <div class="container">
            <a class="navbar-brand" href="#"><i class="fa-solid fa-gamepad"></i>Pro<span
                    class="gamers">gamers</span></a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
                aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <i class="fa-solid fa-bars-staggered"></i>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ms-auto">
                    <a class="nav-link active" href="#home">Home</a>
                    <a class="nav-link" href="#aboutus">o nas</a>
                    <a class="nav-link" href="#portfolio">portfolio</a>
                    <a class="nav-link" href="#prices">ceny</a>
                    <a class="nav-link" href="#team">zespół</a>
                    <a class="nav-link" href="#achievements">osiągnięcia</a>
                    <a class="nav-link" href="#contact">kontakt</a>
                </div>
            </div>
        </div>
    </nav>
    <header id="home">
        <div class="hero-img">
            <div class="hero-shadow"></div>
            <div class="hero-text">
                <h1> witajcie w pro<span class="gamers">gamers</span> </h1>
                <p>W miejscu gdzie gry tworzymy z pasją</p>
                <a href="#aboutus" type="button" class="btn btn-outline-light">poznaj nas</a>
            </div>
            <a href="#aboutus"><i class="fa-solid fa-chevron-down"></i></a>

        </div>
    </header>
    <main>
        <section id="aboutus" class="aboutus bg-light py-5">
            <div class="container">
                <h2>o nas</h2>
                <div class="underline"></div>
                <div class="row">
                    <div class="text-center col-sm-6 col-md-4 aboutus-hover">
                        <p><i class="fa-solid fa-mobile-screen"></i></p>
                        <p class="aboutus-card-title mb-1">mobile gaming</p>
                        <p class="aboutus-card-text">Tworzymy gry na urządzenia mobilne</p>
                    </div>
                    <div class="text-center col-sm-6 col-md-4 aboutus-hover">
                        <p><i class="fa-solid fa-display"></i></p>
                        <p class="aboutus-card-title mb-1">desktop gaming</p>
                        <p class="aboutus-card-text">Tworzymy gry na PC!</p>
                    </div>
                    <div class="text-center col-sm-6 col-md-4 aboutus-hover">
                        <p><i class="fa-solid fa-file-code"></i></p>
                        <p class="aboutus-card-title mb-1">najwyższe standardy</p>
                        <p class="aboutus-card-text">Zachowujemy najwyższe standardy podczas pisania kodu</p>
                    </div>
                    <div class="text-center col-sm-6 col-md-4 aboutus-hover">
                        <p><i class="fa-solid fa-paw"></i></p>
                        <p class="aboutus-card-title mb-1">kochamy zwierzęta!</p>
                        <p class="aboutus-card-text">Wszytskie nasze gry są bezpieczne dla środowiska :)</p>
                    </div>
                    <div class="text-center col-sm-6 col-md-4 aboutus-hover">
                        <p><i class="fa-solid fa-burger"></i></p>
                        <p class="aboutus-card-title mb-1">lubimy dobre jedzenie</p>
                        <p class="aboutus-card-text">Lubimy dobrze zjeść przed przystąpieniem do naszych zadań.</p>
                    </div>
                    <div class="text-center col-sm-6 col-md-4 aboutus-hover">
                        <p><i class="fa-solid fa-champagne-glasses"></i></p>
                        <p class="aboutus-card-title mb-1">świetne relacje</p>
                        <p class="aboutus-card-text">Zachowujemy świetne relacje z naszymi klientami!</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="platform">
            <div class="platform-shadow"></div>
            <div class="container py-3">
                <h2>tworzymy gry na platformy</h2>
                <div class="underline"></div>
                <div class="row">
                    <div class="text-center col-lg-4 platform-item">
                        <p><i class="fa-brands fa-square-steam"></i></p>
                        <p>PC</p>
                        <p>Graj ze znajomymi na swoim blaszaku!</p>
                    </div>
                    <div class="text-center col-lg-4 platform-item">
                        <p><i class="fa-brands fa-playstation"></i></p>
                        <p>PlayStation</p>
                        <p>Gry świetnie prezentują się na konsoli od Sony</p>
                    </div>
                    <div class=" col-lg-4 text-center platform-item">
                        <p><i class="fa-brands fa-xbox"></i></p>
                        <p>Xbox</p>
                        <p>Fani Xboxa spędzą z nami mnóstwo godzin!</p>
                    </div>
                </div>
            </div>
        </section>
        <section id="portfolio" class="portfolio bg-light py-5">
            <h2>portfolio</h2>
            <div class="underline"></div>

            <div class="container">

                <!-- mobile -->

                <div class="card-group d-lg-none ">
                    <div class="card me-sm-3">
                        <img src="./img/console 640.jpeg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to
                                additional content. This content is a little bit longer.</p>
                        </div>
                    </div>
                    <div class="card">
                        <img src="./img/f1 640.jpeg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">This card has supporting text below as a natural lead-in to additional
                                content.</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- desktop -->

            <div id="carouselExampleCaptions" class="carousel slide d-none d-lg-block " data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
                        aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                        aria-label="Slide 2"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="./img/console 1920.jpeg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>First slide label</h5>
                            <p>Some representative placeholder content for the first slide.</p>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <img src="./img/f1c 1920.jpeg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <h5>Second slide label</h5>
                            <p>Some representative placeholder content for the second slide.</p>
                        </div>
                    </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>

        </section>




<div style="height:100vh"></div>
    </main>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
        crossorigin="anonymous"></script>
    <script src="js/script.js"></script>
</body>

</html>
