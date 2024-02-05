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
            <div class="container">
                <div class="contELements">
                    <div class="sign">
                        <button class="btn">SIGN-UP NOW!</button>
                    </div>
                    <nav>
                        <ul class="listClass">
                            <li class="firstLi">FOLLOW US</li>
                            <li><a href="#"><img src="/footer-facebook.png" alt=""></a></li>
                            <li><a href="#"><img src="/footer-twitter.png" alt=""></a></li>
                            <li><a href="#"><img src="/footer-youtube.png" alt=""></a></li>
                            <li><a href="#"><img src="/footer-pinterest.png" alt=""></a></li>
                            <li><a href="#"><img src="/footer-periscope.png" alt=""></a></li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </footer>
</template>
 
<style scoped>
footer {

    background-image: url('/footer-bg.jpg');
    background-size: cover;

    & .footerUp {
        background-image: url('/dc-logo-bg.png');
        background-position: 1000px;
        background-repeat: no-repeat;

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
        background-color: var(--comics-gray);

        & .contELements {
            display: flex;
            justify-content: space-between;
            padding: 0.5rem 0;

            & .sign {
                border: 3px solid var(--comics-blue);
                margin: 2rem 0;

                & .btn {
                    color: var(--comics-light);
                    font-size: 1.5rem;
                    font-weight: 700;
                    background-color: var(--comics-gray);
                    padding: 1rem;
                }
            }

            & nav {
                margin: 2rem 0;


                & .listClass {
                    list-style: none;
                    display: flex;

                    & .firstLi {
                        font-size: 1.5rem;
                        font-weight: 700;
                        color: var(--comics-blue);
                        padding: 1rem;
                    }

                    & img {
                        padding: 1rem 0.5rem;
                    }

                    & a {
                        text-decoration: none;
                        color: var(--comics-gray-text);

                    }
                }

            }
        }
    }
}
</style>