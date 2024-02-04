<script>
export default {
    name: 'AppMain',
}
</script>
 
<template>
    <main>
        <div class="container">
            <div class="black">
                -->contents goes here <-- </div>
            </div>
    </main>
</template>
 
<style>
main {
    background-color: var(--comics-dark);
    min-height: 600px;

    & .black {
        height: 300px;
        color: var(--comics-light);
        font-size: 2rem;
        font-weight: 700;
        padding: 8rem 0;
    }
}
</style>