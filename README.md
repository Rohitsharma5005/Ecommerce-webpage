# Ecommerce-webpage
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Project</title>
  <!-- Bootstrap CSS File -->
  <link href="css/bootstrap.min.css" rel="stylesheet">
  <link href="css/font-awesome.min.css" rel="stylesheet">
  <link href="css/style.css" rel="stylesheet">
</head>

<body>
  <!-- header start -->
  <header class="header" id="header">
    <!-- <div class="topheader bg-danger">
        <button type="button" class="btn btn-outline-dark text-white">Login</button>
        <button type="button" class="btn btn-outline-dark text-white">Signin</button>
      </div> -->
    <nav class="navbar navbar-expand-lg bg-warning">
      <div class="container-fluid">
        <img src="img/logo.png" alt="Logo">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link text-white fs-4" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white fs-4" aria-current="page" href="#">About Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white fs-4" aria-current="page" href="#">Contect Us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white fs-4" aria-current="page" href="#">FAQ</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white fs-4" aria-current="page" href="#">Services</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-white fs-4" aria-current="page" href="#">Gallery</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <!-- header end -->
  <!-- slider section start -->
  <section class="slider" id="slider">
    <div id="carouselExampleCaptions" class="carousel slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
          aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
          aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="img/slider-1.jpg" class="d-block w-100" alt="slider-1">
          <div class="carousel-caption d-none d-md-block text-black">
            <p class="fs-2 fw-bold">Best Smartphone</p>
            <p class="fs-2 fw-bold">Sale Starting At</p>
            <p class="fs-2 fw-bold">$199</p>
            <p>"Effortless innovation, sleek design your perfect companion in the digital world."</p>
            <button class="btn mt-5"><a class="text-white" href="#">Shop Now</a></button>
          </div>
        </div>
        <div class="carousel-item">
          <img src="img/slider-2.jpg" class="d-block w-100" alt="slider-2">
          <div class="carousel-caption d-none d-md-block text-black">
            <p class="fs-2 fw-bold">Best Headphone</p>
            <p class="fs-2 fw-bold">Sale Starting At</p>
            <p class="fs-2 fw-bold">$99</p>
            <p>"Immerse in sound, escape reality with premium, stylish headphones."</p>
            <button class="btn mt-5"><a class="text-white" href="#">Shop Now</a></button>
          </div>
        </div>
        <div class="carousel-item">
          <img src="img/slider-3.jpg" class="d-block w-100" alt="slider-3">
          <div class="carousel-caption d-none d-md-block text-white">
            <p class="fs-2 fw-bold">Get Big Discount This Week</p>
            <p class="fs-2 fw-bold">Big Sale Starting</p>
            <p class="fs-2 fw-bold">Save Upto 80%</p>
            <p>"Biggest Sale of the Year: Unbeatable Discounts Await! Don't Miss Out!"</p>
            <button class="btn mt-5"><a class="text-white" href="#">Shop Now</a></button>
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
  <!-- slider section end -->
  <!-- notification section start -->
  <section class="noti bg-danger d-flex justify-content-center align-items-center pt-3 pb-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 text-white fs-5 ">
          <marquee behavior="alternate">
            Get 55% Off On Your First Order!
          </marquee>
        </div>
      </div>
    </div>
  </section>
  <!-- notification section end -->
  <!-- services section start -->
  <section class="services pt-5 pb-5">
    <div class="container page-builder-ltr">
      <div class="col-xl-12 col-lg-12 col-md-12 col-sm-12 col-xs-12 col-12 col_a9cu  col-style">
        <div class="block-policy">
          <div class="row">
            <div
              class="item col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 d-flex align-items-center justify-content-center">
              <div class="icon pe-3">
                <img src="img/policy-1.png" alt="image">
              </div>
              <div class="info-cont">
                <a class="text-black fs-6 fw-bold text-decoration-none" href="#">Fast & Free Shipping</a>
                <p>Enjoy lightning-fast delivery at no extra cost, because your time matters. Get what you love, faster
                  and free!</p>
              </div>
            </div>
            <div
              class="item col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 d-flex align-items-center justify-content-center">
              <div class="icon pe-3">
                <img src="img/policy-2.png" alt="image">
              </div>
              <div class="info-cont">
                <a class="text-black fs-6 fw-bold text-decoration-none" href="#">30 Days Money Back</a>
                <p>Shop worry-free! If not delighted, we offer a full refund within 30 days. Your satisfaction,
                  guaranteed.</p>
              </div>
            </div>
            <div
              class="item col-xl-4 col-lg-4 col-md-4 col-sm-4 col-12 d-flex align-items-center justify-content-center">
              <div class="icon pe-3">
                <img src="img/policy-3.png" alt="image">
              </div>
              <div class="info-cont">
                <a class="text-black fs-6 fw-bold text-decoration-none" href="#">24/7 Help Center</a>
                <p>Got questions or concerns? Our 24/7 Help Center is here to assist you anytime, anywhere.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- services section end -->
  <!-- products section start -->
  <section class="product pt-5 pb-5">
    <div class="container">
      <div class="row">
        <h2 class="d-flex justify-content-center text-danger mb-3">Featured Products</h2>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-1.jpg" class="card-img-top" alt="">
            <div class="card-body d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Iphone</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star-half-o text-warning"></span>
                <p class="ms-4">$88.00&nbsp;&nbsp;&nbsp;
                <p class="text-decoration-line-through"> $129.00</p>
                </p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-2.jpg" class="card-img-top" alt="">
            <div class="card-body  d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Smartphone</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star-o"></span>
                <p class="ms-4">$59.00&nbsp;&nbsp;&nbsp;
                <p class="text-decoration-line-through"> $79.00</p>
                </p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-3.jpg" class="card-img-top" alt="">
            <div class="card-body  d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Smartphone</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star-o"></span>
                <p class="ms-4">$69.00&nbsp;&nbsp;&nbsp;
                <p class="text-decoration-line-through">$80.00</p>
                </p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-4.jpg" class="card-img-top" alt="">
            <div class="card-body d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Smartphone</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star-o"></span>
                <span class="fa fa-star-o"></span>
                <p class="ms-4">$80.00</p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-5.jpg" class="card-img-top" alt="">
            <div class="card-body d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Laptop</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <p class="ms-4">$899.00&nbsp;&nbsp;&nbsp;
                <p class="text-decoration-line-through"> $999.00</p>
                </p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-6.jpg" class="card-img-top" alt="">
            <div class="card-body d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Laptop</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <p class="ms-4">$799.00</p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-7.jpg" class="card-img-top" alt="">
            <div class="card-body d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Laptop</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star-half-o text-warning"></span>
                <span class="fa fa-star-o"></span>
                <p class="ms-4">$349.00</p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-3 col-lg-4 col-md-6 mb-4">
          <div class="card">
            <img src="img/pro-8.jpg" class="card-img-top" alt="">
            <div class="card-body d-flex flex-column align-items-center justify-content-center">
              <h5 class="card-title text-centerx">Laptop</h5>
              <div class="raring d-flex">
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star text-warning"></span>
                <span class="fa fa-star-o"></span>
                <span class="fa fa-star-o"></span>
                <p class="ms-4">$499.00&nbsp;&nbsp;&nbsp;
                <p class="text-decoration-line-through">$549.00</p>
                </p>
              </div>
              <div class="buy d-flex align-items-center">
                <a class="text-decoration-none service-btn me-5" href="#"><button
                    class="btn btn-outline-success mt-3">Buy Now</button></a>
                <a class="mt-2" href="#"><span class="add_card fa fa-shopping-cart text-danger fs-1"
                    title="Add to Card"></span></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- products section end -->
  <!--Statistics Section start -->
  <section class="pt-5 pb-5">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12 col-12 statistics ">
          <div class="counters-text">
            <span class="title1 backg-gradient p-2 rounded text-white fs-5">
              Our statistics
            </span>
            <h3 class="modtitle mt-3">
              <b> Professional Service &<br> Care In A Pleasant<br> Ambience</b>
            </h3>
            <div class="b-content pb-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse ad necessitatibus odit maiores, reprehenderit vel accusantium suscipit et dolores enim ea dolor corporis itaque eius possimus dolorem iure omnis provident. Odit accusantium nam placeat, omnis sequi, quos vel ex eum in nostrum corporis reiciendis quia, quibusdam alias facere voluptates minus?</div>
          </div>
          <div class="counters-num d-flex gap-5 mt-5 rounded text-white p-4">
            <div class="item">
              <span class="js-counter fw-bold border-end">89k+</span>
              <p>Happy Customers</p>
            </div>
            <div class="item">
              <span class="js-counter fw-bold border-end">27k+</span>
              <p>Products Sold</p>
            </div>
            <div class="item">
              <span class="fw-bold js-counter">15k+</span>
              <p>Years Experience</p>
            </div>
          </div>
        </div>
        <div class="col-xl-6 col-lg-6 col-md-12 col-sm-12 col-12">
          <div class="row">
            <div class="banner col-xl-6 col-lg-6 col-md-6 col-sm-6 col-6">
              <a href="#"><img src="img/service-1.jpg" class="img-fluid" alt="image"></a>
            </div>
            <div class="banner col-xl-6 col-lg-6 col-md-6 col-sm-6 col-6">
              <a href="#"><img src="img/service-2.jpg" class="img-fluid" alt="image"></a>
            </div>
          </div>
          <div class="row">
            <div class="banner col-xl-6 col-lg-6 col-md-6 col-sm-6 col-6">
              <a href="#"><img src="img/service-3.jpg" class="img-fluid" alt="image"></a>
            </div>
            <div class="banner col-xl-6 col-lg-6 col-md-6 col-sm-6 col-6">
              <a href="#"><img src="img/service-4.jpg" class="img-fluid" alt="image"></a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!--Statistics Section end -->

  <!-- Newsletter section start -->

  <!-- newsletter section end -->
  <!-- footer start -->
  <footer class="footer bg-primary pt-5">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4 col-md-6 col-sm-12 footer-content">
          <img src="img/logo.png" alt="logo" style="height: 80px; width:140px;">
          <p class="text-white pt-2">Explore unbeatable deals and top-tier quality at Best Value. Elevate your shopping
            experience with us and discover a world of value-driven purchases that redefine smart shopping. Shop wisely,
            shop Best Value.</p>
        </div>
        <div class="col-xl-4 col-lg-4 col-md-6 col-sm-12 social-icon ps-5">
          <h4 class="text-white">Social Links</h4>

          <p><a class="text-white text-decoration-none" href="#"><i class="fa pe-2 fa-facebook"></i>Facebook</a></p>
          <p><a class="text-white text-decoration-none" href="#"><i class="fa pe-2 fa-instagram"></i>Instagram</a></p>
          <p><a class="text-white text-decoration-none" href="#"><i class="fa pe-2 fa-youtube"></i>YouTube</a></p>
          <p><a class="text-white text-decoration-none" href="#"><i class="fa pe-2 fa-linkedin"></i>Linkedin</a></p>
          <p><a class="text-white text-decoration-none" href="#"><i class="fa pe-2 fa-telegram"></i>Telegram</a></p>
        </div>
        <div class="col-xl-4 col-lg-4 col-md-6 col-sm-12">
          <h4 class="text-white pb-4">Address</h4>
          <p><a class="text-white text-decoration-none" href="tel:0123456789"><i class="fa pe-2 fa-phone"></i>+91 - 012
              345 6789</a></p>
          <p><a class="text-white text-decoration-none" href="bestvalue@gmail.com"><i
                class="fa pe-2 fa-inbox"></i>bestvalue@gmail.com</a></p>
          <address class="text-white">In front of V- Mart Gali, Near the Kali Mata Mandir, Naka Chungi, Paharganj Road,
            Ayodhya U.P. 224001</address>
        </div>
      </div>
  </footer>
  <!-- Footer section End -->

  <!-- js file link -->
  <script src="js/bootstrap.bundle.min.js"></script>
  <script src="js/jquery.js"></script>
  <script>
    $(document).ready(function () {
      $(window).scroll(function () {
        if ($(this).scrollTop() > 90) {
          $("#header").addClass('sticky');
        } else {
          $("#header").removeClass('sticky');
        }
      })
    })

  </script>

</body>

</html>
This is my first Git project.
