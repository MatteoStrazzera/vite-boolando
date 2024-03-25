<script>
export default {
    name: 'ProductCard'
}
</script>

<template>

    <div class="img-container">
        <div class="image">
            <img src="" alt="">
            <img class="hover-img" src="" alt="">
        </div>
        <div class="heart">&hearts;</div>
        <div class="discount"></div>
        <div class="sustain"></div>
        <ul class="product-description">
            <li class="product-brand"></li>
            <li class="product-name"><strong></strong></li>
            <li class="product-price">
                <span class="discount-price"><strong> &euro;</strong></span>
                <span class="old-price"> &euro;</span>
            </li>
        </ul>
    </div>

</template>

<style></style>