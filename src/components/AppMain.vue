<script>
import AppBlueRibbon from './AppBlueRibbon.vue';

export default {
    name: 'AppMain',
    components: {
        AppBlueRibbon,
    }
}

</script>
 
<template>
    <main>
        <div class="mainUp">
            <div class="container">
                contents goes here
            </div>
        </div>
        <AppBlueRibbon></AppBlueRibbon>
    </main>
</template>
 
<style scoped>
main {
    /* min-height: 600px; */
}

.mainUp {
    background-color: var(--comics-dark);
    height: 300px;
    color: var(--comics-light);
    font-size: 2rem;
    font-weight: 700;
    padding: 8rem 0;
}
</style>