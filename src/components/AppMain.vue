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

    <!-- Navigation button -->
    <a class="nav_button p-0" href="#header">
      <div class="wrapper px-2 py-1">
        <i class="bi bi-chevron-double-up"></i>
      </div>
    </a>

    <!-- Banner -->
    <AppBanner />

    <!-- Shopping info -->
    <div class="custom-container">

      <ul class="shopping_info list-unstyled d-flex align-items-center px-5">

        <li class="free_delivery">
          <a class=" d-flex align-items-center flex-fill gap-3" href="">

            <i class="fa-solid fa-truck-fast fa-2xl"></i>
            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Free Delivery</span>
              <span class="poppins-regular">Free Shipping On All Order</span>
            </div>

          </a>
        </li>

        <li class="px-5">|</li>

        <li class="money_policy">
          <a class=" d-flex align-items-center flex-fill gap-3" href="">

            <i class="fa-solid fa-sack-dollar fa-2xl"></i>
            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Money Return</span>
              <span class="poppins-regular">Back Guarantee in 7 days</span>
            </div>

          </a>
        </li>

        <li class="px-5">|</li>

        <li class="member_discount">
          <a class=" d-flex align-items-center flex-fill gap-3" href="">

            <i class="fa-solid fa-certificate fa-2xl">
              <span>%</span>
            </i>

            <div class="description d-flex flex-column">
              <span class="oxanium-semibold">Member Discount</span>
              <span class="poppins-regular">On every order over €130.00</span>
            </div>

          </a>
        </li>

        <li class="px-5">|</li>

        <li class="return_policy">
          <a class="d-flex align-items-center flex-fill gap-3" href="">

            <i class="fa-solid fa-hand-holding-dollar fa-2xl"></i>
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
            <div class="_card">
              <div class="shop_cta">
                <span>Batman</span>
                <span>Shop Now</span>
              </div>

            </div>
          </div>

          <div class="col">
            <div class="_card">
              <div class="shop_cta">
                <span>Bayonetta</span>
                <span>Shop Now</span>

              </div>
            </div>
          </div>

          <div class="col">
            <div class="_card">
              <div class="shop_cta">
                <span>Dark Souls</span>
                <span>Shop Now</span>
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

      <!-- Secton navbar -->
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
        <div class="row row-cols-4">

          <div class="col">

            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

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

              <!-- <div class="foreground"></div> -->

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

      <!-- Secton navbar -->
      <ul class="nav">

        <li class="nav-item oxanium-semibold">
          <a class="nav-link" href="#">1026 days</a>
        </li>

        <li class="nav-item oxanium-semibold">
          <a class="nav-link" href="#">13 hours</a>
        </li>

        <li class="nav-item oxanium-semibold">
          <a class="nav-link" href="#">24 mins</a>
        </li>

        <li class="nav-item oxanium-semibold">
          <a class="nav-link" href="#">17 secs</a>
        </li>

      </ul>

      <!-- Product cards -->
      <div class="custom-container">
        <div class="row row-cols-4">

          <div class="col">

            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="product_card">

              <div class="card_image"></div>

              <div class="card_footer">

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

            <div class="article_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="article_card">

              <div class="card_image"></div>

              <div class="card_footer">

              </div>

            </div>
          </div>

          <div class="col">
            <div class="article_card">

              <div class="card_image"></div>

              <div class="card_footer">

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
