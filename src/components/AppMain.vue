<script>
import ProductCard from './ProductCard.vue';

export default {
    name: 'AppMain',
    components: {
        ProductCard
    }
}
</script>

<template>
    <main class="site-main">
        <div class="container d-flex-wrap">
            <div class="img-container">
                <div class="image">
                    <img src="/public/images/1.webp" alt="">
                    <img class="hover-img" src="/public/images/1b.webp" alt="">
                </div>
                <div class="heart">&hearts;</div>
                <div class="discount">-50%</div>
                <div class="sustain">Sostenibilità</div>
                <ul class="product-description">
                    <li class="product-brand">Levi's</li>
                    <li class="product-name"><strong>RELAXED FIT TEE UNISEX</strong></li>
                    <li class="product-price">
                        <span class="discount-price"><strong>14,99 &euro;</strong></span>
                        <span class="old-price">29,99 &euro;</span>
                    </li>
                </ul>
            </div>
            <div class="img-container">
                <div class="image">
                    <img src="/public/images/2.webp" alt="">
                    <img class="hover-img" src="/public/images/2b.webp" alt="">
                </div>
                <div class="heart">&hearts;</div>
                <div class="discount">-30%</div>
                <ul class="product-description">
                    <li class="product-brand">Guess</li>
                    <li class="product-name"><strong>ROSES TEE</strong></li>
                    <li class="product-price">
                        <span class="discount-price"><strong>20,99 &euro;</strong></span>
                        <span class="old-price">29,99 &euro;</span>
                    </li>
                </ul>
            </div>
            <div class="img-container">
                <div class="image">
                    <img src="/public/images/3.webp" alt="">
                    <img class="hover-img" src="/public/images/3b.webp" alt="">
                </div>
                <div class="heart">&hearts;</div>
                <div class="discount">-30%</div>
                <ul class="product-description">
                    <li class="product-brand">Come Zucchero Filato</li>
                    <li class="product-name"><strong>VOGLIA DI COLORI PASTELLO</strong></li>
                    <li class="product-price">
                        <span class="discount-price"><strong>129,99 &euro;</strong></span>
                        <span class="old-price">184,99 &euro;</span>
                    </li>
                </ul>
            </div>
            <div class="img-container">
                <div class="image">
                    <img src="/public/images/4.webp" alt="">
                    <img class="hover-img" src="/public/images/4b.webp" alt="">
                </div>
                <div class="heart">&hearts;</div>
                <div class="discount">-50%</div>
                <div class="sustain">Sostenibilità</div>
                <ul class="product-description">
                    <li class="product-brand">Levi's</li>
                    <li class="product-name"><strong>TEE UNISEX</strong></li>
                    <li class="product-price">
                        <span class="discount-price"><strong>14,99 &euro;</strong></span>
                        <span class="old-price">29,99 &euro;</span>
                    </li>
                </ul>
            </div>
            <div class="img-container">
                <div class="image">
                    <img src="/public/images/5.webp" alt="">
                    <img class="hover-img" src="/public/images/5b.webp" alt="">
                </div>
                <div class="heart">&hearts;</div>
                <ul class="product-description">
                    <li class="product-brand">Maya Deluxe</li>
                    <li class="product-name"><strong>STRIPE BODICE</strong></li>
                    <li class="product-price">
                        <span class="discount-price"><strong>99,99 &euro;</strong></span>
                    </li>
                </ul>
            </div>
            <div class="img-container">
                <div class="image">
                    <img src="/public/images/6.webp" alt="">
                    <img class="hover-img" src="/public/images/6b.webp" alt="">
                </div>
                <div class="heart">&hearts;</div>
                <div class="sustain2">Sostenibilità</div>
                <ul class="product-description">
                    <li class="product-brand">Esprit</li>
                    <li class="product-name"><strong>MAGLIONE-BLACK</strong></li>
                    <li class="product-price">
                        <span class="discount-price"><strong>29,99 &euro;</strong></span>
                    </li>
                </ul>
            </div>
        </div>
    </main>
</template>

<style></style>