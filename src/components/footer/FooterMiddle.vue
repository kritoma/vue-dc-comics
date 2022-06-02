<template>
  <div class="footer_middle">
      <div class="container">
          <div class="flex">
            <div class="list-footer">
                    <div class="column">
                        <div>
                            <h3>DC COMICS</h3>
                            <ul>
                                <li>Characters</li>
                                <li>Comics</li>
                                <li>Movies</li>
                                <li>TV</li>
                                <li>Games</li>
                                <li>Video</li>
                                <li>News</li>
                            </ul>
                        </div>
                        <div>
                            <h3>SHOP</h3>
                            <ul>
                                <li>Shop DC</li>
                                <li>Shop DC Collectibles</li>
                            </ul>
                        </div>
                    </div>
                    <div class="column">
                        <h3>DC</h3>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choicces</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                    <div class="column">
                        <h3>SITES</h3>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
            </div>
            <div class="logo_footer">
                <img src="../../assets/img/dc-logo-bg.png" alt="logo">
            </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name : "FooterMiddle",
}
</script>

<style lang="scss" scoped>
.footer_middle {
    background-image: url('../../assets/img/footer-bg.jpg');
    height: 25rem;
    overflow: hidden;

    .flex {
        display: flex;
        justify-content: space-between;

        .list-footer {
            display: flex;
            gap: 1.25rem;
            color: white;
            margin-top: 1.875rem;
           



            ul {
                list-style: none;
                margin: .9375rem 0 ;
                color: #959595;

                li {
                    margin: .5rem 0;
                }
        
            }
        }

        .logo_footer {
            height: 100%;
            

            img {
                position: relative;
                bottom: 5.625rem;
            }
        }
    }
}
</style>