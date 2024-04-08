<script>

export default {
  name: 'AppHeader'
}

</script>

<template>

  <header class="poppins-regular" id="header">


    <div class="custom-container info">

      <ul class="d-flex list-unstyled p-0 m-0">
        <li><a href="">Whishlist (0)</a></li>
        <li class="px-3">|</li>
        <li class="flex-fill">
          <a href="">Need Help ? </a>
          <i class="fa-solid fa-chevron-down fa-xs"></i>
        </li>
        <li><a href="">Call 24/7 . 800-8754-987</a></li>
      </ul>

    </div>

    <hr class="m-0">

    <div class="custom-container menu d-flex align-items-center justify-content-between">

      <div class="logo">
        <img src="/public/images/logo.png" alt="">
      </div>

      <ul class="navbar d-flex list-unstyled play-bold gap-5 p-0 m-0">
        <li><a href="">Home</a></li>
        <li><a href="">Shop</a></li>
        <li><a href="">Blog</a></li>
        <li><a href="">Media</a></li>
        <li><a href="">ShortCode</a></li>
        <li><a href="">Features</a></li>
      </ul>

      <ul class="profile-icons list-unstyled play-bold d-flex gap-4 p-0 m-0">
        <li><a href=""><i class="fa-solid fa-magnifying-glass"></i></a></li>
        <li><a href=""><i class="fa-regular fa-user"></i></a></li>
        <li>
          <a href=""><i class="fa-solid fa-bag-shopping"></i></a>
          (0) €0.00
        </li>
      </ul>

    </div>

  </header>


</template>

<style></style>
