<template>
    <div class="footer_top">
         <div class="container">
            <ul>
                <li>
                    <img src="../../assets/img/buy-comics-merchandise.png" alt="merchandise">
                    <span>DC MERCHANDISE</span>
                </li>
                 <li>
                    <img src="../../assets/img/buy-comics-subscriptions.png" alt="merchandise">
                    <span>SUBSCRIPTION</span>
                </li>
                 <li>
                    <img src="../../assets/img/buy-comics-shop-locator.png" alt="merchandise">
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                 <li>
                    <img src="../../assets/img/buy-dc-power-visa.svg" alt="merchandise">
                    <span>DC POWER VISA</span>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: "FooterTop",
}
</script>

<style lang="scss" scoped>
.footer_top {
    background-color: var(--color-primary);
    padding: 1.875rem 0;

    ul {
        display: flex;
        list-style: none;
        justify-content: center;
        gap: 1.875rem;

        li {
            display: flex;
            align-items: center;

            img {
                height: 3rem;
                margin-right: .9375rem;
            }

            span {
                color: white;
            }
        }
    }
}
</style>