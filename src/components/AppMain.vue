<script>
import AppBanner from './AppBanner.vue';


export default {
  name: 'AppMain',
  components: {
    AppBanner
  }
}

</script>

<template>

  <main id="main">

    <!-- Site Navigation button -->
    <a class="site_nav_button p-0" href="#header">
      <div class="wrapper px-2 py-1">
        <i class="bi bi-chevron-double-up"></i>
      </div>
    </a>


    <!-- Banner -->
    <AppBanner />


    <!-- Shopping info -->
    <div class="custom-container">

      <ul class="shopping_info list-unstyled d-flex justify-content-between align-items-center px-5">

        <li>
          <a class=" d-flex align-items-center flex-fill gap-3" href="">

            <div class="free_delivery"></div>

            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Free Delivery</span>
              <span class="poppins-regular">Free Shipping On All Order</span>
            </div>

          </a>
        </li>

        <li class="px-4">|</li>

        <li>
          <a class=" d-flex align-items-center flex-fill gap-3" href="">

            <div class="money_policy"></div>

            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Money Return</span>
              <span class="poppins-regular">Back Guarantee in 7 days</span>
            </div>

          </a>
        </li>

        <li class="px-4">|</li>

        <li>
          <a class=" d-flex align-items-center flex-fill gap-3" href="">

            <div class="member_discount"></div>

            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Member Discount</span>
              <span class="poppins-regular">On every order over €130.00</span>
            </div>

          </a>
        </li>

        <li class="px-4">|</li>

        <li>
          <a class="d-flex align-items-center flex-fill gap-3" href="">

            <div class="return_policy"></div>

            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Return policy</span>
              <span class="poppins-regular">Support 24 hours a day</span>
            </div>

          </a>
        </li>

      </ul>
    </div>


    <!-- Games Adv -->
    <div class="games_adv">
      <div class="custom-container">
        <div class="row row-cols-2">

          <div class="col">

            <div class="game_adv_card">

              <div class="description d-flex flex-column justify-content-center">

                <div class="label">
                  <h5 class="oxanium-semibold ps-3 m-0">Most Popular</h5>
                </div>

                <h4 class="game_title oxanium-semibold m-0">The Battlefield 4 Naval Strike</h4>

              </div>
            </div>

          </div>

          <div class="col">

            <div class="game_adv_card">

              <!-- <div class="foreground"></div> -->

              <div class="description d-flex flex-column justify-content-center">

                <div class="label">
                  <h3 class="oxanium-semibold ps-3 m-0">Latest Game</h3>
                </div>

                <h1 class="game_title oxanium-semibold m-0">Assassin's Creed Unity Game</h1>

              </div>

            </div>

          </div>

        </div>
      </div>
    </div>


    <!-- Special Category -->
    <div class="debug special_category">

      <!-- Section title -->
      <h4 class="section_title oxanium-semibold mx-auto">Special Category</h4>

      <hr class="divider mx-auto">

      <!-- Game cards -->
      <div class="custom-container">
        <div class="row row-cols-3">

          <div class="col">
            <div class="_card d-flex justify-content-start align-items-end" title="Battlefield 3">
              <div class="shop_cta d-flex flex-column px-3 pb-3 pt-4">
                <span class="game_title oxanium-semibold mb-2">Battlefield 3</span>
                <span class="cta_link poppins-regular">
                  <a href="">Shop Now</a>
                </span>
              </div>
            </div>
          </div>

          <div class="col">
            <div class="_card d-flex justify-content-start align-items-end" title="PlayerUnknown's Battlegrounds">
              <div class="shop_cta d-flex flex-column px-3 pb-3 pt-4">
                <span class="game_title oxanium-semibold mb-2">PlayerUnknown's Battlegrounds</span>
                <span class="cta_link poppins-regular">
                  <a href="">Shop Now</a>
                </span>
              </div>
            </div>
          </div>

          <div class="col">
            <div class="_card d-flex justify-content-start align-items-end" title="Jump Force">
              <div class="shop_cta d-flex flex-column px-3 pb-3 pt-4">
                <span class="game_title oxanium-semibold mb-2">Jump Force</span>
                <span class="cta_link poppins-regular">
                  <a href="">Shop Now</a>
                </span>
              </div>
            </div>
          </div>

        </div>
      </div>

    </div>


    <!-- Our Products -->
    <div id="our_products" class="debug d-flex flex-column align-items-center">

      <!-- Section title -->
      <h4 class="section_title oxanium-semibold mx-auto">Our Products</h4>

      <hr class="divider mx-auto">

      <!-- Navbar -->
      <ul class="nav">

        <li class="nav-item poppins-bold">
          <a class="nav-link" href="#">Featured</a>
        </li>

        <li class="nav-item poppins-bold">
          <a class="nav-link" href="#">New Arrival</a>
        </li>

        <li class="nav-item poppins-bold">
          <a class="nav-link" href="#">Best Seller</a>
        </li>

      </ul>

      <!-- Product cards -->
      <div class="custom-container">

        <!-- Navigation buttons -->
        <div class="prev"></div>
        <div class="next"></div>

        <div class="row row-cols-4">

          <div class="col">

            <!-- Product card -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2 ">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">PC Gamepad - Black</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 70.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>
            </div>
          </div>

          <div class="col">

            <!-- Product card -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">AverMedia GM310 Aegis USB microphone</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 83.00 - € 90.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>
            </div>
          </div>

          <div class="col">

            <!-- Product card -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">Redragon Gaming MousePad - Black&Red</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 39.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>
            </div>
          </div>

          <div class="col">

            <!-- Product card -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">Sony DualShock 4 Wireless - Black</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 110.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>
      </div>

    </div>


    <!-- Games Discount-->
    <div class="games_discount">
      <div class="custom-container">
        <div class="row row-cols-2">

          <div class="col">

            <div class="game_adv_card">

              <div class="description d-flex flex-column justify-content-center">

                <div class="label">
                  <h5 class="oxanium-semibold ps-3 m-0">20% Discount</h5>
                </div>

                <h4 class="game_title oxanium-semibold m-0">Dragon's Dogma Video Game</h4>

              </div>
            </div>

          </div>

          <div class="col">

            <div class="game_adv_card">

              <div class="description d-flex flex-column justify-content-center">

                <div class="label">
                  <h3 class="oxanium-semibold ps-3 m-0">30% Discount</h3>
                </div>

                <h1 class="game_title oxanium-semibold m-0">World Of Tanks New Game</h1>

              </div>

            </div>

          </div>

        </div>
      </div>
    </div>


    <!-- Deal Of The Day -->
    <div class="debug deal_of_the_day d-flex flex-column align-items-center">

      <!-- Section title -->
      <h4 class="section_title oxanium-semibold mx-auto">Deal Of The Day</h4>

      <hr class="divider mx-auto">

      <!-- Timer navbar -->
      <ul class="timer list-unstyled d-flex">

        <li class="timer-item oxanium-semibold">
          <a class="timer-link" href="#">1026 days</a>
        </li>

        <li class="timer-item oxanium-semibold">
          <a class="timer-link" href="#">13 hours</a>
        </li>

        <li class="timer-item oxanium-semibold">
          <a class="timer-link" href="#">24 mins</a>
        </li>

        <li class="timer-item oxanium-semibold">
          <a class="timer-link" href="#">17 secs</a>
        </li>

      </ul>

      <!-- Product cards -->
      <div class="custom-container">

        <!-- Navigation buttons -->
        <div class="prev"></div>
        <div class="next"></div>

        <div class="row row-cols-4">

          <div class="col">

            <!-- Product card -->
            <div class="product_card">

              <!-- Discount label -->
              <div class="label">
                <p class="oxanium-semibold m-0">-44%</p>
              </div>

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2 ">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">Sony DualShock 4 Wireless - Urban Camo</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="discounted_price oxanium-semibold me-2">€ 180.00</span>
                  <span class="actual_price oxanium-semibold">€ 100.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>
            </div>
          </div>

          <div class="col">

            <!-- Product title -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">Razer Mamba - Gaming Mouse</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 56.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>
            </div>
          </div>

          <div class="col">

            <!-- Product title   -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">Gaming Headset Black</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 39.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>
            </div>
          </div>

          <div class="col">

            <!-- Product card -->
            <div class="product_card">

              <!-- Image -->
              <div class="card_image"></div>

              <!-- Card footer -->
              <div class="card_footer d-flex flex-column align-items-between px-2">

                <!-- Rating stars -->
                <div class="rating d-flex align-items-center mt-3">

                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>
                  <i class="fa-solid fa-star"></i>

                </div>

                <!-- Product title -->
                <div class="product_title oxanium-semibold mt-3">
                  <a href="">Gamepad PC - Orange</a>
                </div>

                <!-- Price -->
                <div class="price my-3">
                  <span class="actual_price oxanium-semibold">€ 160.00</span>
                </div>

                <!-- User actions -->
                <div class="user_actions d-flex">

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-regular fa-hand-pointer"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-heart"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-maximize"></i>
                    </a>
                  </div>

                  <div class="icon_container text-center py-1">
                    <a href="">
                      <i class="fa-solid fa-eye"></i>
                    </a>
                  </div>

                </div>

              </div>

            </div>

          </div>

        </div>
      </div>
    </div>


    <!-- Customers Review -->
    <div class="customers_review">
      <div class="container-fluid">

        <div class="carousel">

          <div class="background d-flex align-items-end justify-content-center">

            <div class="content d-flex flex-column align-items-center justify-content-center">

              <div class="customer_pic">
                <img src="/images/t5-1-100x100_left.jpg" alt="">
                <div>
                  <i class="fa-solid fa-quote-left"></i>
                </div>
              </div>

              <div class="customer_name">
                <span class="oxanium-semibold me-2">Luies Charles</span>
                <span class="oxanium-semibold">(Web Designer)</span>
              </div>

              <div class="customer_quote poppins-regular">
                "There are many variations of passages of Lorem Ipsum available, but the majority have suffered
                alteration
                in some form, by injected humour, There are many variations of passages of Lorem Ipsum available, but
                the
                majority have suffered alteration in some form, by injected humour, There are many variations of
                passages
                of
                Lorem Ipsum available"
              </div>

              <div class="navigation">
                <ul class="list-unstyled d-flex align-items-center">

                  <li>
                    <a href="">
                      <i class="fa-solid fa-circle"></i>
                    </a>
                  </li>

                  <li>
                    <a href="">
                      <i class="fa-solid fa-circle"></i>
                    </a>
                  </li>

                  <li>
                    <a href="">
                      <i class="fa-solid fa-circle"></i>
                    </a>
                  </li>

                </ul>



              </div>

            </div>
          </div>


        </div>

      </div>
    </div>


    <!-- Blog -->
    <div id="blog">

      <!-- Section title -->
      <h4 class="section_title oxanium-semibold mx-auto">New Game Blogs</h4>

      <hr class="divider mx-auto">

      <!-- Articles -->
      <div class="custom-container">
        <div class="row row-cols-3">

          <div class="col">

            <!-- Arcticle -->
            <div class="article_card">

              <!-- Image -->
              <div class="card_image"></div>

              <div class="card_footer">

                <div class="date_and_comments poppins-regular d-flex align-items-center mt-3 mb-2">
                  <i class="fa-regular fa-calendar-days me-1"></i>
                  <span class="me-4">Jan 18, 2024</span>
                  <i class="fa-solid fa-comments me-1"></i>
                  <span>0 comments</span>
                </div>

                <!-- Article title -->
                <div class="article_title oxanium-semibold">
                  Anyway REPS is a NYC agency repres enting photographers
                </div>

              </div>

            </div>

          </div>

          <div class="col">

            <!-- Article -->
            <div class="article_card">

              <!-- Image -->
              <div class="card_image"></div>

              <div class="card_footer">

                <div class="date_and_comments poppins-regular d-flex align-items-center mt-3 mb-2">
                  <i class="fa-regular fa-calendar-days me-1"></i>
                  <span class="me-4">Feb 30, 2024</span>
                  <i class="fa-solid fa-comments me-1"></i>
                  <span>0 comments</span>
                </div>

                <!-- Article title -->
                <div class="article_title oxanium-semibold">
                  Nasual risus suscipit Lorem ipsum is simply text
                </div>

              </div>

            </div>

          </div>

          <div class="col">

            <!-- Article -->
            <div class="article_card">

              <!-- Image -->
              <div class="card_image"></div>

              <div class="card_footer">

                <div class="date_and_comments poppins-regular d-flex align-items-center mt-3 mb-2">
                  <i class="fa-regular fa-calendar-days me-1"></i>
                  <span class="me-4">Apr 5, 2024</span>
                  <i class="fa-solid fa-comments me-1"></i>
                  <span>0 comments</span>
                </div>
                <!-- Article title -->
                <div class="article_title oxanium-semibold">
                  Nostrum lesum Christum Lorem ipsum is simply text
                </div>

              </div>

            </div>

          </div>

        </div>

        <hr class="divider_big">

      </div>
    </div>


    <!-- Brands -->
    <div class="brands">
      <div class="custom-container">

        <ul class="list-unstyled d-flex align-items-center justify-content-between px-5">

          <li>
            <img src="/images/brand-01.png" alt="">
          </li>

          <li>
            <img src="/images/brand-02.png" alt="">
          </li>

          <li>
            <img src="/images/brand-03.png" alt="">
          </li>

          <li>
            <img src="/images/brand-04.png" alt="">
          </li>

          <li>
            <img src="/images/brand-05.png" alt="">
          </li>

        </ul>

      </div>

    </div>

  </main>

</template>

<style></style>
