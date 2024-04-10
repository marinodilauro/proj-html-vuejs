<script>

export default {
  name: 'AppFooter'
}

</script>

<template>

  <footer id="footer" class="poppins-regular d-flex flex-column justify-content-end align-items-center">

    <div class="custom-container footer_top">
      <div class="container-fluid">
        <div class="row row-cols-4">

          <!-- Address Info -->
          <div class="col">
            <ul class="list-unstyled">

              <li class="oxanium-semibold list_title mb-3">Address Info</li>

              <li class="lh-lg mb-2">
                <i class="fa-solid fa-location-dot pe-3"></i>
                <a href="">60 29th Street San Francisco. CA 94110 507-Union Trade Center, United States of America</a>
              </li>

              <li class="lh-lg mb-2">
                <i class="fa-solid fa-phone pe-3"></i>
                <a href="">(+00) 123-456-789</a>
              </li>

              <li class="lh-lg mb-2">
                <i class="fa-solid fa-envelope pe-3"></i>
                <a href="">demo@example.com</a>
              </li>

            </ul>
          </div>

          <!-- Informations -->
          <div class="col">
            <ul class="list-unstyled m-0">

              <li class="oxanium-semibold list_title mb-3">Informations</li>

              <li class="lh-lg mb-2">
                <a href="">Bookmarks</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">Features</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">Sitemap</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">Lists</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">Contact Us</a>
              </li>

            </ul>
          </div>

          <!-- Extras -->
          <div class="col">
            <ul class="list-unstyled m-0">

              <li class="oxanium-semibold list_title mb-3">Extras</li>

              <li class="lh-lg mb-2">
                <a href="">Delivery</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">Cart</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">Terms and conditions</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">My account</a>
              </li>

              <li class="lh-lg mb-2">
                <a href="">About Us</a>
              </li>

            </ul>
          </div>

          <!-- Our Newsletter -->
          <div class="col">
            <ul class="list-unstyled m-0">

              <li class="oxanium-semibold list_title mb-3">Our Newsletter</li>

              <li class="lh-lg mb-4">
                There are many variations of passages of form humour or randomised
              </li>

              <li class="lh-lg mb-4">

                <div class="input-group">
                  <input class="newsletter_input" type="text" name="newsletter" id="newsletter">

                  <button class="newsletter_btn" type="button" id="button-addon2">
                    <div class="newsletter_icon"></div>
                  </button>
                </div>

              </li>

              <li class="lh-lg mb-2">
                <ul class="social_icons list-unstyled d-flex gap-4 m-0">

                  <li>
                    <a href=""><i class="fa-brands fa-facebook-f fa-lg"></i></a>
                  </li>

                  <li>
                    <a href=""><i class="fa-brands fa-x-twitter fa-lg"></i></a>
                  </li>

                  <li>
                    <a href=""><i class="fa-brands fa-google-plus-g fa-lg"></i></a>
                  </li>

                  <li>
                    <a href=""><i class="fa-brands fa-skype fa-lg"></i></a>
                  </li>

                  <li>
                    <a href=""><i class="fa-brands fa-instagram fa-lg"></i></a>
                  </li>

                </ul>
              </li>

            </ul>
          </div>

        </div>
      </div>
    </div>

    <hr class="mt-5">

    <div class="custom-container footer_bottom d-flex justify-content-between align-items-center pb-1">

      <!-- Copyright -->
      <span>Copyright &copy; 2024 Marino di Lauro</span>

      <!-- Payment Methods -->
      <ul class="payment_methods d-flex list-unstyled p-0 m-0 gap-1">

        <li class="amex"></li>
        <li class="discover"></li>
        <li class="mastercard"></li>
        <li class="paypal"></li>
        <li class="visa"></li>

      </ul>

    </div>

  </footer>

</template>

<style></style>
