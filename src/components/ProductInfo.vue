<template>
    <div>
        <h3>Freshness</h3>
        <p>Our coffee was literally picked 2 hours ago</p>
        <h3>Quality</h3>
        <p>We only take 1% of the beans that we pick</p>
        <h3>Exclusive</h3>
        <p>You need to be a member to get the coffee, which automatically raises intrisic value.</p>
        <product-gallery></product-gallery>
    </div>
</template>

<script>
import ProductGallery from '@/components/ProductGallery.vue'
export default {
    components: {
        ProductGallery
    }
}
</script>

<style scoped>

</style>