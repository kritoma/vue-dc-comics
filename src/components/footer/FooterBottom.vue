<template>
  <div class="footer-bottom">
      <div class="container">
          <div>
              <button>SIGN-UP NOW!</button>
          </div>
          <div class="social">
              <h3>FOLLOW US</h3>
              <img src="../../assets/img/footer-facebook.png" alt="">
              <img src="../../assets/img/footer-twitter.png" alt="">
              <img src="../../assets/img/footer-youtube.png" alt="">
              <img src="../../assets/img/footer-pinterest.png" alt="">
              <img src="../../assets/img/footer-periscope.png" alt="">
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "FooterBottom"
}
</script>

<style lang="scss" scoped>
.footer-bottom {
    background-color: #303030;
    padding: 1.875rem 0;

    .container {
        display: flex;
        justify-content: space-between;
        align-items: center;

        button {
            background-color: #303030;
            color: white;
            font-weight: 600;
            border: 1px solid var(--color-primary);
            padding: .625rem .9375rem;
        }

        .social {
            display: flex;
            align-items: center;
            gap: 1.25rem;

            h3 {
                color: var(--color-primary);
                font-weight: 600;
            }
        }
    }
}
</style>