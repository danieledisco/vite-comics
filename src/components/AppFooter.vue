<script>
export default {
    name: 'AppFooter',

}
</script>
 
<template>
    <footer>
        <div class="footerUp">

        </div>
        <div class="footerDown">

        </div>
    </footer>
</template>
 
<style scoped>
footer {
    min-height: 600px;
    background-image: url('/dc-logo-bg.png'), url('/footer-bg.jpg');
    background-size: auto, cover;
    background-repeat: no-repeat, no-repeat;
    background-position: right top, center;

    & .footerUp {
        height: 400px;
    }

    & .footerDown {
        height: 200px;
        background-color: var(--comics-gray);
    }
}
</style>