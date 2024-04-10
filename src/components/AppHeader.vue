<script>

export default {
  name: 'AppHeader'
}

</script>

<template>

  <header class="poppins-regular" id="header">

    <div class="custom-container info">

      <!-- Header top -->
      <ul class="d-flex list-unstyled p-0 m-0">
        <li><a href="">Whishlist (0)</a></li>
        <li class="px-3">|</li>
        <li>
          <a href="">Need Help ? </a>
          <i class="fa-solid fa-chevron-down fa-xs"></i>
        </li>
        <li class="ms-auto"><a href="">Call 24/7 . 800-8754-987</a></li>
      </ul>

    </div>

    <hr class="m-0">

    <!-- Header Menu -->
    <div class="custom-container menu d-flex align-items-center justify-content-between">

      <div class="logo">
        <img src="/images/logo.png" alt="">
      </div>

      <ul class="navbar d-flex list-unstyled oxanium-bold gap-5 p-0 m-0">
        <li><a href="">Home</a></li>
        <li><a href="#our_products">Shop</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="">Media</a></li>
        <li><a href="">ShortCode</a></li>
        <li><a href="">Features</a></li>
      </ul>

      <ul class="icon_group list-unstyled oxanium-bold d-flex gap-4 p-0 m-0">

        <li>
          <a href="">
            <div class="search_icon"></div>
          </a>
        </li>

        <li>
          <a href="">
            <div class="profile_icon"></div>
          </a>
        </li>

        <li class="d-flex justify-content-center">
          <a href="">
            <div class="shop_icon me-2"></div>
          </a>
          <span class="align-self-baseline">(0) €0.00</span>
        </li>

      </ul>

    </div>

  </header>

</template>

<style></style>
