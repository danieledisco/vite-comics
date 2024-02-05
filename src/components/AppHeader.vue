<script>
export default {
    name: 'AppHeader',
}
</script>
 
<template>
    <header>
        <div class="container">
            <div class="contELements">
                <div class="logo">
                    <img src="/dc-logo.png" alt="">
                </div>
                <nav>
                    <ul class="main_menu">
                        <li><a href="#">CHARACTERS</a></li>
                        <li><a href="#" class="active">COMICS</a></li>
                        <li><a href="#">MOVIES</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">GAMES</a></li>
                        <li><a href="#">COLLECTIBLES</a></li>
                        <li><a href="#">VIDEOS</a></li>
                        <li><a href="#">FANS</a></li>
                        <li><a href="#">NEWS</a></li>
                        <li><a href="#">SHOP</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>
 
<style scoped>
header {
    background-color: var(--compics-light);
    margin-bottom: 1px;

    & .contELements {
        display: flex;
        justify-content: space-between;
        padding: 0.5rem 0;

        & .main_menu {
            margin-top: 2rem;
            list-style: none;
            display: flex;
            justify-content: flex-end;

            & a {
                text-decoration: none;
                padding-top: 3.6rem;
                padding-bottom: 3.6rem;
                margin-left: 0.5rem;
                margin-right: 0.5rem;
                color: var(--comics-dark);
                font-weight: 700;
            }

            & a.active {
                color: var(--comics-blue);
                border-bottom: 6px solid var(--comics-blue);

            }
        }
    }
}
</style>