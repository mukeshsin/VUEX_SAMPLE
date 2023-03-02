<template>
<div id="app">
    <product-list-one></product-list-one>
    <product-list-two></product-list-two>
    <product-list-three></product-list-three>
</div>
</template>

<script>
import ProductListOne from './components/ProductListOne.vue'
import ProductListTwo from './components/ProductListTwo.vue'
import ProductListThree from './components/ProductListThree.vue'

export default {
    name: 'ProductLists',
    components: {
        ProductListOne,
        ProductListTwo,
        ProductListThree
    },
    data() {
        return {

        }
    }
}
</script>

<style>

</style>
