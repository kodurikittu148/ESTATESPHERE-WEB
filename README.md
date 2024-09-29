# ESTATESPHERE-WEB
we are trying to build a realstate website where customer need to register in this website and can choose a land or a property which meets their requirement and if a person wanted to sell a property they need to approach us to verify their documents of the property and get access
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    </style>
</head>
<body>
    <!-- Main Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
        <div class="container d-flex justify-content-between">
            <!-- EstateSphere Logo -->
            <a class="navbar-brand" href="#">Estate<span class="text-warning">Sphere</span></a>
            <!-- Search Engine Form and About/Contact -->
            <div class="d-flex align-items-center">
                <form class="d-flex me-3" role="search" style="width: 400px;">
                    <input class="form-control me-2" type="text" placeholder="City Name" aria-label="City Name" style="width: 100%;">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
                <!-- About Us and Contact Us -->
                <ul class="navbar-nav d-flex flex-row align-items-center">
                    <li class="nav-item">
                        <a class="nav-link" href="#About Us">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#Contact Us">Contact Us</a>
                    </li>
                    <!-- Hamburger Menu Dropdown -->
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="dropdownMenuButton" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            <div class="hamburger-icon">
                                <span></span>
                                <span></span>
                                <span></span>
                            </div>
                        </a>
                        <ul class="dropdown-menu dropdown-menu-end" aria-labelledby="dropdownMenuButton">
                            <li><a class="nav-link" href="Login and registration.html">Login/Register</a></li>
                            <li><a class="nav-link" href="#For Buyers">For Buyers</a></li>
                            <li><a class="nav-link" href="#For Sellers">For Sellers</a></li>
                            <li><a class="nav-link" href="#For Dealers">For Dealers</a></li>
                            <li><a class="nav-link" href="#For Builders">For Builders</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Secondary Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light fixed-top navbar-secondary" style="top: 70px; background-color: transparent; border: none;">
      <div class="container">
          <div class="collapse navbar-collapse d-flex justify-content-center" id="navbarSupportedContent">
              <ul class="navbar-nav mb-2 mb-lg-0">
                  <li class="nav-item">
                      <a class="nav-link" href="#For Buyers">For Buyers</a>
                  </li>
                  <li class="nav-item">
                      <a class="nav-link" href="#For Sellers">For Sellers</a>
                  </li>
                  <li class="nav-item">
                      <a class="nav-link" href="#For Dealers">For Dealers</a></li>
                  <li class="nav-item">
                      <a class="nav-link" href="#For Builders">For Builders</a></li>
              </ul>
          </div>
      </div>
  </nav>
    <!-- Carousel -->
    <div id="carouselExampleDark" class="carousel carousel-dark slide mt-0">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="3" aria-label="Slide 4"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active" data-bs-interval="10000">
                <img src="download1.jpeg" class="d-block w-100" alt="Apartment at Warangal">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Apartment at Warangal</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                    <p><a href="#" class="btn btn-warning">Learn More</a></p>
                </div>
            </div>
            <div class="carousel-item" data-bs-interval="2000">
                <img src="download2.jpeg" class="d-block w-100" alt="Second Slide">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Second slide label</h5>
                    <p>Some representative placeholder content for the second slide.</p>
                    <p><a href="#" class="btn btn-warning">Learn More</a></p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="download3.jpeg" class="d-block w-100" alt="Third Slide">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Third slide label</h5>
                    <p>Some representative placeholder content for the third slide.</p>
                    <p><a href="#" class="btn btn-warning">Learn More</a></p>
                </div>
            </div>
            <div class="carousel-item">
              <img src="download4.jpeg" class="d-block w-100" alt="Third Slide">
              <div class="carousel-caption d-none d-md-block">
                  <h5>Third slide label</h5>
                  <p>Some representative placeholder content for the third slide.</p>
                  <p><a href="#" class="btn btn-warning">Learn More</a></p>
              </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js"></script>
</body>
</html>
