<script>
export default {
    name: 'AppFooter',

}
</script>
 
<template>
    <footer>
        <div class="footerUp">
            <div class="container">
                <div class="row">
                    <div class="col">

                        <h2>DC COMICS</h2>
                        <ul class="listClass">
                            <li><a href="#">Characters</a> </li>
                            <li><a href="#">Comics</a> </li>
                            <li><a href="#">Movies</a> </li>
                            <li><a href="#">TV</a> </li>
                            <li><a href="#">Games</a> </li>
                            <li><a href="#">Videos</a> </li>
                            <li><a href="#">News</a> </li>
                        </ul>

                        <h2>SHOP</h2>
                        <ul class="listClass">
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>

                    <div class="col">
                        <h2>DC</h2>
                        <ul class="listClass">
                            <li><a href="#">Terms Of Use</a> </li>
                            <li><a href="#">Provacy policy (New)</a> </li>
                            <li><a href="#">Ad Chocices</a> </li>
                            <li><a href="#">Advertising</a> </li>
                            <li><a href="#">Jobs</a> </li>
                            <li><a href="#">Subscriptions</a> </li>
                            <li><a href="#">CPSC Cetificates</a> </li>
                            <li><a href="#">Ratings</a> </li>
                            <li><a href="#">Shop Help</a> </li>
                            <li><a href="#">Contact Us</a> </li>
                        </ul>
                    </div>

                    <div class="col">
                        <h2>SITES</h2>
                        <ul class="listClass">
                            <li><a href="#">DC</a> </li>
                            <li><a href="#">MAS Magazie</a> </li>
                            <li><a href="#">DC Kids</a> </li>
                            <li><a href="#">DC Universe</a> </li>
                            <li><a href="#">DC Power Visa</a> </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="footerDown">

        </div>
    </footer>
</template>
 
<style scoped>
footer {
    background-image: url('/dc-logo-bg.png'), url('/footer-bg.jpg');
    background-size: auto, cover;
    background-repeat: no-repeat, no-repeat;
    background-position: right top, center;

    & .footerUp {
        & h2 {
            color: var(--comics-light);
            padding: 0.8rem 0;
        }

        & .listClass {
            list-style: none;

            & a {
                text-decoration: none;
                color: var(--comics-gray-text);

            }
        }
    }

    & .footerDown {
        height: 200px;
        background-color: var(--comics-gray);
    }
}
</style>