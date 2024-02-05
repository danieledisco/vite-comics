<script>
export default {
    name: 'AppMain',
}

</script>
 
<template>
    <main>
        <div class="mainUp">
            <div class="container">
                contents goes here
            </div>
        </div>
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
    </main>
</template>
 
<style scoped>
main {
    min-height: 600px;
}

.mainUp {
    background-color: var(--comics-dark);
    height: 300px;
    color: var(--comics-light);
    font-size: 2rem;
    font-weight: 700;
    padding: 8rem 0;
}

.mainDown {
    background-color: var(--comics-blue);
    padding: 4rem 0;

    & .col {
        display: flex;
        color: var(--comics-light);

        & .cardImage {
            text-align: center;
            width: var(--comics-card-image-width);
            color: var(--comics-light);

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

.svg {
    z-index: 100;
}
</style>