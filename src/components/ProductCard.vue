<script>
export default {
    name: 'ProductCard',
    props: {
        product: {
            type: Object,
        }
    }
}
</script>

<template>

    <div class="img-container">
        <div class="image">
            <img :src="product.firstImage" alt="">
            <img class="hover-img" :src="product.secondImage" alt="">
        </div>
        <div class="heart">&hearts;</div>
        <div class="discount">{{ product.discount }}</div>
        <div class="sustain">{{ product.specialTag }}</div>
        <ul class="product-description">
            <li class="product-brand">{{ product.brand }}</li>
            <li class="product-name"><strong>{{ product.productName }}</strong></li>
            <li class="product-price">
                <span class="discount-price"><strong>{{ product.price.discountedPrice }} &euro;</strong></span>
                <span class="old-price">{{ product.price.oldPrice }} &euro;</span>
            </li>
        </ul>
    </div>

</template>

<style></style>