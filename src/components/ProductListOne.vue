<template>
<div class="product-list">
    <h2 class="head">Product List1</h2>
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
    name: 'productListOne',
    computed: {
        products() {
        return this.$store.state.products
        }
    }
}
</script>

