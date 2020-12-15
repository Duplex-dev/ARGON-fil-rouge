<template>
  <footer class="footer has-cards">
    <!-- <div class="container container-lg">
            <div class="row">
                <div class="col-md-6 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/landing" title="Landing Page">
                            <img v-lazy="'img/theme/landing.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
                <div class="col-md-6 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <router-link to="/profile" title="Profile Page">
                            <img v-lazy="'img/theme/profile.jpg'" class="card-img">
                        </router-link>
                    </div>
                </div>
            </div>
        </div> -->
    <div class="container-fluid">
      <div class="col-lg-6 btn-wrapper">
        <a
          target="_blank"
          rel="noopener"
          href="https://instagram.com"
          class="btn btn-neutral btn-icon-only btn-instagram btn-round btn-lg"
          data-toggle="tooltip"
          data-original-title="Follow us"
        >
          <i class="fa fa-instagram"></i>
        </a>
        <a
          target="_blank"
          rel="noopener"
          href="https://www.facebook.com"
          class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg"
          data-toggle="tooltip"
          data-original-title="Like us"
        >
          <i class="fa fa-facebook-square"></i>
        </a>

        <a
          target="_blank"
          rel="noopener"
          href="https://snapchat.com"
          class="btn btn-neutral btn-icon-only btn-snapchat btn-round btn-lg"
          data-toggle="tooltip"
          data-original-title="Star on Github"
        >
          <i class="fa fa-snapchat"></i>
        </a>
      </div>
      <div class="liens utiles">
        <h4>Liens utiles</h4>
      </div>
      <div class="row align-items-center">
        <div class="politiques col-md-6">
          <ul class="politics">
            <li><a href="#">Politique de confidentialité </a></li>
            <li><a href="#">Politique de remboursement</a></li>
            <li><a href="#">CGV et d'Utilisation </a></li>
            <li><a href="#">FAQ-Questions fréquentes</a></li>
          </ul>
        </div>
      </div>
      <hr />
      <div class="row align-items-center justify-content-md-between">
        <div class="col-md-6">
          <div class="copyright">
            &copy; {{ year }}
            <a
              href="https://www.creative-tim.com"
              target="_blank"
              rel="noopener"
              >She<span class="rose">.</span>Only</a
            >
            <!-- &
            <a href="https://www.binarcode.com" target="_blank" rel="noopener"
              >Binar Code</a -->
          </div>
        </div>
        <div class="col-md-6">
          <ul class="nav nav-footer justify-content-end">
            <li class="nav-item">
              <a href="#" class="nav-link" target="_blank" rel="noopener"
                ><i class="fab fa-cc-visa"></i
              ></a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link" target="_blank" rel="noopener"
                ><i class="fab fa-cc-mastercard"></i
              ></a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link" target="_blank" rel="noopener"
                ><i class="fab fa-cc-apple-pay"></i
              ></a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link" target="_blank" rel="noopener"
                ><i class="fab fa-paypal"></i
              ></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "app-footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style>
</style>
