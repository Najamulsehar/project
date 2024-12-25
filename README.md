# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard</title>
    <!-- bs link -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css">
    <!-- css file-->
     <link rel="stylesheet" href="external files/style.css">
</head>
<body>
    <!-- section 1 start -->
    <div class="container-fluid">
        <div class="row">
            <div class="col-3">
                <div class="section1">
                    <h1>Online Learning</h1>
                    <ul class="mt-5">
                        <li class="mt-5"><i class="fa-solid fa-table-columns"></i> <a href="#">Dashboard</a></li>
                        <li class="mt-4"><i class="fa-solid fa-address-card"></i><a href="external files/about.html">About Us</a></li>
                        <li class="mt-4"><i class="fa-solid fa-phone"></i><a href="external files/contact.html">Contact Us</a></li>
                        <li class="mt-4"><i class="fa-solid fa-address-book"></i> <a href="external files/register.html">Register</a></li>
                    </ul>
                </div>
            </div>
            <!-- section 1 end -->


            <!-- head start -->
            <!-- column 2 -->
            <div class="col-9">
              <div class="search-box">
                  <form class="d-flex">
                      <input type="search" class="form-control me-2 mt-4" placeholder="Search" id="input-box" autocomplete="off">
                      <button class="btn btn-outline-primary mt-4">Search</button>
                  </form>
                  <div class="result-box">
                      
                  </div>
              </div>
                <!-- head end -->


                <!-- button foe d-m -->
                <!-- <div class="form-check form-switch mx-2">
                  <input
                  type="checkbox" 
                  class="form-check-input p-2" 
                  role="switch"
                   id="flexSwitchCheckChecked"
                  onclick="myfunction()">
                </div> -->



                
                <!-- section 2 main -->
                <div class="section2">
                    <h1>Dashboard</h1>
                    <!-- row 1 -->
                    <div class="row mt-4">
                        <div class="col">
                            <div class="card" style="width: 18rem;">
                                <img src="images/html.jpeg" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h4>Learn HTML</h4>
                                  <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                                    <br><a href="https://www.w3schools.com/html/">Learn More</a>
                                  </p>

                                </div>
                              </div>
                        </div>
                        <div class="col">
                            <div class="card" style="width: 18rem;">
                                <img src="images/css.jpeg" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h4>Learn CSS</h4>
                                  <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                                    <br><a href="https://www.w3schools.com/css/">Learn More</a>
                                  </p>

                                </div>
                              </div>
                        </div>
                        <div class="col">
                            <div class="card" style="width: 18rem;">
                                <img src="images/java.png" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h4>JavaScript</h4>
                                  <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                                    <br><a href="https://www.w3schools.com/js/">Learn More</a>
                                  </p>

                                </div>
                              </div>
                        </div>
                    </div>
                    <!-- row 1 end -->

                    <!-- row 2 -->
                    <div class="row mt-5 mb-5">
                        <div class="col">
                            <div class="card" style="width: 18rem;">
                                <img src="images/e-commerce.jpg" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h4>E-Commerce</h4>
                                  <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                                    <br><a href="https://sell.amazon.com/learn/what-is-ecommerce">Learn More</a>
                                  </p>

                                </div>
                              </div>
                        </div>
                        <div class="col">
                            <div class="card" style="width: 18rem;">
                                <img src="images/jquery.avif" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h4>Learn Jquery</h4>
                                  <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                                    <br><a href="https://www.w3schools.com/jquery/default.asp">Learn More</a>
                                  </p>

                                </div>
                              </div>
                        </div>
                        <div class="col">
                            <div class="card" style="width: 18rem;">
                                <img src="images/wordpress.jpg" class="card-img-top" alt="...">
                                <div class="card-body">
                                  <h4>Wordpress</h4>
                                  <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                                    <br><a href="https://www.tutorialspoint.com/wordpress/index.htm">Learn More</a>
                                  </p>

                                </div>
                              </div>
                        </div>
                    </div>
                    <!-- row 2 end -->
                </div>
                <!-- section 2 end -->
            </div>
        </div>
    </div>

    <!-- <script>
      function myfunction(){
        var element=document.body;
        document.dataset.bsTheme=
        document.dataset.bsTheme== "light"? "dark":"light";
      }
    </script> -->
    <script src="external files/search.js"></script>
</body>
</html>
