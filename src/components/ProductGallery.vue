<template>
    <div>
        <img src="~@/assets/product1.jpg" alt="">
        <img src="~@/assets/product2.jpg" alt="">
        <img src="~@/assets/product3.jpg" alt="">
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    div {
        display: grid;
        place-items: center;
        width: 100%;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }

    img {
        max-width: 100%;
    }
</style>