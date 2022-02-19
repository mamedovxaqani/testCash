<template>
  <footer class="footer">
    <div class="footer__container">
      <div class="footer__left">
        <div class="footer__nav">
          <ul class="footer__navbar">
            <li class="footer__navbar-item">
              <a href="" class="footer__navbar-link">How it works</a>
            </li>
            <li class="footer__navbar-item">
              <a href="" class="footer__navbar-link">Why choose us</a>
            </li>
            <li class="footer__navbar-item">
              <a href="" class="footer__navbar-link">FAQs</a>
            </li>
            <li class="footer__navbar-item">
              <a href="" class="footer__navbar-link">Contact</a>
            </li>
          </ul>
        </div>
        <div class="footer__author">
          <span class="footer__text">
            @{{ year }} Cash for Cars | Terms and Conditions | Privacy
            Policy</span
          >
        </div>
      </div>
      <div class="footer__right">
        <div class="footer__logo">CashForCars</div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
