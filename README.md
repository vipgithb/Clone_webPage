# Clone_webPage
Here I tried to clone a web page.
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
      crossorigin="anonymous"
    />

    <!-- custom css -->
    <link rel="stylesheet" href="style.css" />
    <title>Flash Food</title>
  </head>
  <body>
    <!-- nav bar -->
    <nav class="navbar navbar-expand-lg header" id="myHeader">
      <div class="container-fluid">
        <a class="navbar-brand fw-bold text-white" href="#">FlashFood</a>
        <button
          class="navbar-toggler bg-light"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon fw-bolder">--</span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#howItWorks">How It Works</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Location</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                About
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li><a class="dropdown-item" href="#">Our Story</a></li>
                <li><a class="dropdown-item" href="#">Food Waste</a></li>
                <li><a class="dropdown-item" href="#">The Team</a></li>
                <li><a class="dropdown-item" href="#">Press Room</a></li>
                <li><a class="dropdown-item" href="#">Impact Report</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Support</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Partner</a>
            </li>
            <li class="nav-item">
              <button class="button-74" role="button">Download</button>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div
      class="container-fluid text-white pb-5"
      style="background-color: rgba(66, 48, 221, 0.8)"
    >
      <div class="row" style="height: 120px"></div>
      <div class="row">
        <div class="col offset-2" style="width: 60%">
          <h1 class="fw-bold">Save money and fight against food waste</h1>
          <p class="mt-2">
            Get massive savings on fresh food items like meat and produce that
            are nearing their best before date at grocery stores across Canada
            and the U.S.
          </p>
          <ul
            class="d-flex justify-content-between"
            style="list-style-type: none"
          >
          <li class="mx-2"><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/5e4dd1dd09d48f7b3cf2bdf4_Google%201.svg" alt=""></li>
            <li><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/5e4dd1e309d48fb5d5f2be24_Apple%201.svg" alt=""></li>
            <li>
              <a class="text-decoration-none text-white" href="#"
                >How it works ></a
              >
            </li>
          </ul>
        </div>
        <div class="col offset-2">
          <img
            style="mix-blend-mode: color-burn; aspect-ratio: 3/4"
            src="https://thumbs.dreamstime.com/b/click-touch-screen-smartphone-modern-smartsphone-hand-clicking-screen-finger-click-mobile-phone-action-apps-141616291.jpg"
            width="50%"
            alt=""
          />
        </div>
      </div>
    </div>

    <!-- partners -->
    <div class="container mt-5">
      <div class="card" style="box-shadow: 2px 2px 10px rgba(77, 77, 102, 0.5)">
        <div class="card-body">
          <ul class="list-unstyled d-flex justify-content-lg-evenly">
            <li>
              <img
                style="aspect-ratio: 4/4; object-fit: cover"
                src="	https://assets-global.website-files.com/5e596dafce8eb6216f68e410/6160917b1a8635a54d0474b5_meijer.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 3/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/64a5c41bf724bb41dfb7e64d_Kroger%3DColour%20Logo-p-500.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 4/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/6160915588d55b4f0856ffcd_giant.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 5/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/61609143a31417a81a957ae4_giant-martins.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 4/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/6160914b792d8c1e70357323_sn-martins.png"
                width="90px"
                alt=""
              />
            </li>
          </ul>
          <ul class="list-unstyled d-flex justify-content-lg-evenly">
            <li>
              <img
                style="aspect-ratio: 4/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/6160914fbdb50d4274adf3a7_tops.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 4/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/61609161bc65c04d70b91fb5_familyfare.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 4/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/616091491da266b91553e11d_giant-eagle.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 5/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/61f9aa9bafd4220683c28567_VGs_logo7.png"
                width="90px"
                alt=""
              />
            </li>
            <li>
              <img
                style="aspect-ratio: 6/4; object-fit: cover"
                src="https://assets-global.website-files.com/5e596dafce8eb6216f68e410/6160913fbdb50d1257ade855_stop-and-shop.png"
                width="90px"
                alt=""
              />
            </li>
          </ul>
          <div class="text-center mt-5">
            <button
              class="btn btn-outline-dark btn-sm"
              style="border-radius: 30px"
            >
              See more
            </button>
            <div class="row">
              <div class="col-3"></div>
              <div
                class="col-7 align-self-center card mt-5"
                style="box-shadow: 2px 2px 10px rgba(77, 77, 102, 0.5)"
              >
                <div
                  class="card-body d-flex align-items-center justify-content-center"
                >
                  <p class="mx-2 my-2">
                    Are you a grocery chain that wants to work with Flashfood?
                  </p>
                  <button class="btn btn-primary">Learn More</button>
                </div>
              </div>
              <div class="col"></div>
            </div>
          </div>
        </div>
         <!-- how it works -->
        <div class="container mt-5">
          <h1 class="text-center" id="howItWorks">How it Works</h1>
          <div
            class="card m-5"
            style="border-radius: 10px; background-color: #f2f2ff"
          >
            <div class="card-body">
              <div class="row">
                <div class="col-7 m-4">
                  <h3 class="mt-4 fw-bold">
                    First, use the free app to quickly and easily find
                    discounted food from wherever you are.
                  </h3>
                  <ul class="mt-5 text-secondary mx-3">
                    <li class="mt-2">
                      <p>
                        Browse deals of up to 50% off at a grocery store
                        location near you.
                        <a style="text-decoration: none" href=""
                          >See Locations ></a
                        >
                      </p>
                    </li>
                    <li class="mt-2">Choose your discounted food items.</li>
                    <li class="mt-2">
                      Pay right in the app using any major credit card, VISA
                      debit card, or SNAP EBT card.
                    </li>
                  </ul>
                </div>
                <div class="col-4">
                  <img
                    src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/636bdc73528dc750114b5323_ebt_homepagepic-p-800.png"
                    class="img-fluid"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>

          <div
            class="card m-5"
            style="border-radius: 10px; background-color: #f2f2ff"
          >
            <div class="card-body">
              <div class="row">
                <div class="col-4">
                  <img
                    src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/5e83642b21df556cf89a8a01_person-fridge-p-500.png"
                    class="img-fluid"
                    style="aspect-ratio: 2/2; object-fit: contain"
                    alt=""
                  />
                </div>
                <div class="col-7 m-4">
                  <h3 class="mt-4 fw-bold">
                    Then, pick up your Flashfood order at the grocery store.
                  </h3>
                  <p class="mt-3 text-secondary">
                    Head to the store, grab your food items from the Flashfood
                    zone, and quickly confirm your order with the customer
                    service desk.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div
            class="card m-5"
            style="border-radius: 10px; background-color: #f2f2ff"
          >
            <div class="card-body">
              <div class="row">
                <div class="col-7 m-4">
                  <h3 class="mt-4 fw-bold">
                    Finally, enjoy good food, a great deal, and the good deed -
                    you just saved some food from the landfill!
                  </h3>
                  <a class="mt-3 text-decoration-none">
                    Learn more about Food Waste >
                  </a>
                </div>
                <div class="col-4">
                  <img
                    src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/5e50882a8c34f83e2341e710_image.png"
                    class="img-fluid"
                    style="aspect-ratio: 2/2; object-fit: contain"
                    alt=""
                  />
                </div>
              </div>
            </div>
          </div>

          <!-- comments -->
          <div class="container">
            <h2
              class="text-center offset-3 fw-bold"
              style="margin-top: 150px; max-width: 50%"
            >
              We’ve helped thousands of people save money on their groceries
            </h2>

            <div
              class="card m-5"
              style="box-shadow: 2px 2px 10px rgba(77, 77, 102, 0.5)"
            >
              <div class="card-body p-4 d-grid">
                <img
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079edaef8efe087dde4d7fd_quotation.svg"
                  width="40"
                  alt="Quotation"
                />
                <img
                  class="mt-3"
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/61016f0960ab7abb8864a98e_stars.svg"
                  width="110"
                  alt=""
                />
                <p class="mt-3 small">
                  Another day and another box of fruit bought off the Flashfood
                  app! I love using this app and keeping perfectly good food
                  from going into the landfill. All of the food posted on the
                  app is reaching its best before date but still perfectly good
                  to eat. And it was only $5.00! 😊
                </p>
                <h6 class="fw-bold mt-3 small">
                  @ACELIACSTRAVELS FROM AIRDRIE, ALBERTA
                </h6>
              </div>
            </div>
            <div
              class="card m-5"
              style="box-shadow: 2px 2px 10px rgba(77, 77, 102, 0.5)"
            >
              <div class="card-body p-4 d-grid">
                <img
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079edaef8efe087dde4d7fd_quotation.svg"
                  width="40"
                  alt="Quotation"
                />
                <img
                  class="mt-3"
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/61016f0960ab7abb8864a98e_stars.svg"
                  width="110"
                  alt=""
                />
                <p class="mt-3 small">
                  I despise wasting food, and I love getting a great deal.
                  flashfood makes it so simple for me to actually save food
                  destined for the dump, and all they ask is that I pay a
                  fraction of the price for it. In my personal opinion, the food
                  is fine! No issues whatsoever! In what world does this service
                  not make perfect sense?
                </p>
                <h6 class="fw-bold mt-3 small">PETER T. FROM TORONTO</h6>
              </div>
            </div>
            <div
              class="card m-5"
              style="box-shadow: 2px 2px 10px rgba(77, 77, 102, 0.5)"
            >
              <div class="card-body p-4 d-grid">
                <img
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079edaef8efe087dde4d7fd_quotation.svg"
                  width="40"
                  alt="Quotation"
                />
                <img
                  class="mt-3"
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/61016f0960ab7abb8864a98e_stars.svg"
                  width="110"
                  alt=""
                />
                <p class="mt-3 small">
                  Wow! I am absolutely delighted with my first box! A great
                  selection of produce (carrots, English cucumber, peppers,
                  mushrooms, onions, apples, oranges and the protein (kielbasa,
                  chicken meatballs, teriyaki chicken meatballs, pulled chicken)
                  was awesome as well! Will most certainly order again!
                </p>
                <h6 class="fw-bold mt-3 small">
                  PAULINE P. FROM WYANDOTTE, MICHIGAN
                </h6>
              </div>
            </div>
            <div
              class="card m-5"
              style="box-shadow: 2px 2px 10px rgba(77, 77, 102, 0.5)"
            >
              <div class="card-body p-4 d-grid">
                <img
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079edaef8efe087dde4d7fd_quotation.svg"
                  width="40"
                  alt="Quotation"
                />
                <img
                  class="mt-3"
                  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/61016f0960ab7abb8864a98e_stars.svg"
                  width="110"
                  alt=""
                />
                <p class="mt-3 small">
                  Love it. between the wife and I who have the app on both our
                  phones, we saved over $1200. instead of stores throwing out
                  expired food to the dump, they can get rid of food when it's
                  close to expiration dates. love it. I highly recommend it.
                </p>
                <h6 class="fw-bold mt-3 small">BRETT C. FROM AJAX</h6>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
    <!-- download section -->
    <div class="container-fluid mt-5" style=" background-color: #4230dd;">
      <div class="row mt-5">
          <div class="col-6 mt-5 offset-1 text-white" style="width: 30%;">
          <h5 class="text-white-50">ARE YOU READY?</h5>
          <h1 class="mt-3">Download the free app and save money on groceries now</h1>
          <ul
          class="d-flex mt-4"
          style="list-style-type: none"
        >
          <li class="mx-2"><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/5e4dd1dd09d48f7b3cf2bdf4_Google%201.svg" alt=""></li>
          <li><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/5e4dd1e309d48fb5d5f2be24_Apple%201.svg" alt=""></li>
         
        </ul>
          </div>
          <div class="col-6">
              <img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/607f342e86767b926943b932_flashfood-phone-cta-sfw.jpg" class="img-fluid" alt="">
          </div>
             </div>
    </div>
    <!-- footer -->
    <div class="container-fluid p-5" style="background-color: #06022b;">
        <div class="fw-bold text-white d-flex justify-content-end" ><p>Follow @flashfood</p></div>

        <ul class="d-flex justify-content-evenly " >
            <li>
                        <img class="img img-fluid p-1"  src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079b4bf46b89d3095d43c44_%40buffalofooood.jpg" loading="lazy" alt="A young woman smiling holding up her Flashfood haul which includes various fruits, spinach, bagels, hummus and cheese" class="footer-photo">
                        
                    </li>
                    <li>
                        
                        <img class="img img-fluid p-1"   src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079b4cc2af973049f73bfe1_%40detroitfather.jpg" loading="lazy" alt="A man and his daughter smiling, standing next to the Flashfood fridge in the store" class="footer-photo">
                    </li>
                    <li>
                        
                        <img class="img img-fluid p-1"   src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079b4dd83b02737a2ce6ea9_%40shoshana.jpg" loading="lazy" alt="A Flashfood haul that includes chicken breasts, sausages, bagged salad, hummus, snap peas, and pineapple" class="footer-photo">
                    </li>
                    <li>
                        
                        <img class="img img-fluid p-1"   src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079b4e8f8596474f6a68911_%40thefunemployedfamily.jpg" loading="lazy" alt="A woman juggling oranges from a Flashfood fruit box with her small daughter sitting next to her laughing" class="footer-photo">
                    </li>
                    <li>
                        <img class="img img-fluid p-1"   src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079b50f16c3352a86643dba_%40undeniableannie.jpg" loading="lazy" alt="Woman standing next to the Flashfood fridge in the store" class="footer-photo">
                        
                    </li>
                   
            </ul>

            <div class="row mt-5 text-white d-flex justify-content-between" >
                <div class="col-4 " style="max-width: 20%;">
            
                    <h4>Find Flashfood near you →</h4>
                    <div>
                        <a aria-label="Instagram icon" href="#"><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079eac5223122b8ffa160df_insta-mint.svg" alt="Instagram icon"></a>
                        <a aria-label="Facebook icon" href="#"><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079eac56256cf0580a0319d_fb-mint.svg" alt="Facebook icon" ></a>
                        <a aria-label="Twitter icon" href="#"><img src="https://assets-global.website-files.com/5e4482baa13a1926b23e2187/6079eac5d03463ecbdc7a983_twitter-mint.svg" alt="Twitter icon"></a>
                    </div>
                </div>
                <div class="col-2">
                    <ul class="list-unstyled fw-bold" style="line-height:35px;">
                        <li>The Team</li>
                        <li>Locations</li>
                        <li>Our Story</li>
                        <li>Food Waste</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul class="list-unstyled fw-bold" style="line-height:35px;">
                        <li>News</li>
                        <li>Blog</li>
                        <li>Refer A Friend</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul class="list-unstyled fw-bold" style="line-height:35px;">
                        <li>Partner</li>
                        <li>Careers</li>
                        <li>Support</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul class="list-unstyled fw-bold" >
                        <li  style="line-height:35px;">Terms of Use</li>
                        <li style="line-height:35px;">Privacy Policy</li>
                        <li style="line-height:25px;">Supplier Diversity Policy</li>
                        <li style="line-height:25px;">Responsible Disclosure</li>
                    </ul>
                </div>
            </div>
            <div class="container mt-5 text-white-50 d-flex justify-content-end"><p>© Flashfood Inc. 2023. All rights reserved.</p></div>
        </div>

   

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
      crossorigin="anonymous"
    ></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    -->

    <!-- header script -->
    <script>
      // When the user scrolls the page, execute myFunction
      window.onscroll = function () {
        myFunction();
      };

      // Get the header
      var header = document.getElementById("myHeader");

      // Get the offset position of the navbar
      var sticky = header.offsetTop;

      // Add the sticky class to the header when you reach its scroll position. Remove "sticky" when you leave the scroll position
      function myFunction() {
        if (window.pageYOffset > sticky) {
          header.classList.add("sticky");
        } else {
          header.classList.remove("sticky");
        }
      }
    </script>
  </body>
</html>
