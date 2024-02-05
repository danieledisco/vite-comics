<script>
export default {
    name: 'AppBlueRibbon',

}
</script>
 
<template>
    <div class="mainDown">
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="cardImage">
                        <img src="/buy-comics-digital-comics.png" alt="">
                    </div>
                    <div class="cardName">
                        DIGITAL COMICS
                    </div>
                </div>
                <div class="col">
                    <div class="cardImage">
                        <img src="/buy-comics-merchandise.png" alt="">
                    </div>
                    <div class="cardName">
                        DC MERCHANDISE
                    </div>

                </div>
                <div class="col">
                    <div class="cardImage">
                        <img src="/buy-comics-subscriptions.png" alt="">
                    </div>
                    <div class="cardName">
                        SUBSCRIPTION
                    </div>

                </div>

                <div class="col">
                    <div class="cardImage">
                        <img src="/buy-comics-shop-locator.png" alt="">
                    </div>
                    <div class="cardName">
                        COMIC SHOP LOCATOR
                    </div>

                </div>
                <div class="col">
                    <div class="cardImage">
                        <img src="/buy-dc-power-visa.svg" alt="">

                    </div>
                    <div class="cardName">
                        DC POWER VISA
                    </div>

                </div>

            </div>

        </div>
    </div>
</template>
 
<style scoped>
.mainDown {
    background-color: var(--comics-blue);
    padding: 2rem 0;

    & .col {
        display: flex;
        color: var(--comics-light);

        & .cardImage {
            margin-left: 2.5rem;
            text-align: center;
            color: var(--comics-light);
            margin-top: auto;
            margin-bottom: auto;

            & img {
                width: var(--comics-card-image-width);
            }
        }

        & .cardName {
            font-size: 0.8rem;
            text-align: center;
            margin-top: auto;
            margin-bottom: auto;
            margin-left: 0.5rem;
            white-space: nowrap;
        }

    }
}
</style>