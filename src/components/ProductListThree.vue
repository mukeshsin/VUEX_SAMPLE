<template>
<div class="product-list">
    <h2 class="head">Product List3</h2>
    <ul class="cssWrap">
        <li v-for="product in products" :key="product.id" class="para">
            <span class="name">{{ product.name }}</span>
            <span class="price">${{ product.price }}</span>
        </li>

    </ul>
</div>
</template>

<script>
export default {
    name: 'productListThree',
    computed: {
        products() {
            return this.$store.state.products
        }
    }
}
</script>

<style>

</style>
