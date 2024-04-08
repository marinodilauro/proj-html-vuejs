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

    <AppBanner />

    <!-- Shopping info -->
    <div class="custom-container">

      <ul class="shopping_info list-unstyled d-flex align-items-center px-5 m-0">

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
        <div class="d-flex justify-content-between">

          <div class="col me-3">

            <div class="description d-flex flex-column justify-content-center">

              <div class="label">
                <h5 class="oxanium-semibold ps-3 m-0">Most Popular</h5>
              </div>

              <h4 class="game_title oxanium-semibold m-0">The Battlefield 4 Naval Strike</h4>

            </div>

          </div>

          <div class="col ms-3">

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



  </main>


</template>

<style></style>
