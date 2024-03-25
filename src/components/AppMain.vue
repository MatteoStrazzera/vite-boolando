<script>
import ProductCard from './ProductCard.vue';

export default {
    name: 'AppMain',
    components: {
        ProductCard
    },
    data() {
        return {
            products: [
                {
                    id: 1,
                    firstImage: '/public/images/1.webp',
                    secondImage: '/public/images/1b.webp',
                    discount: '-50%',
                    specialTag: 'Sostenibilità',
                    brand: 'Levi\'s',
                    productName: 'RELAXED FIT TEE UNISEX',
                    price: {
                        discountedPrice: 14.99,
                        oldPrice: 29.99
                    }
                },
                {
                    id: 2,
                    firstImage: '/public/images/2.webp',
                    secondImage: '/public/images/2b.webp',
                    discount: '-30%',
                    brand: 'Guess',
                    productName: 'ROSES TEE',
                    price: {
                        discountedPrice: 20.99,
                        oldPrice: 29.99
                    }
                },
                {
                    id: 3,
                    firstImage: '/public/images/3.webp',
                    secondImage: '/public/images/3b.webp',
                    discount: '-30%',
                    brand: 'Come Zucchero Filato',
                    productName: 'VOGLIA DI COLORI PASTELLO',
                    price: {
                        discountedPrice: 129.99,
                        oldPrice: 184.99
                    }
                },
                {
                    id: 4,
                    firstImage: '/public/images/4.webp',
                    secondImage: '/public/images/4b.webp',
                    discount: '-50%',
                    specialTag: 'Sostenibilità',
                    brand: 'Levi\'s',
                    productName: 'TEE UNISEX',
                    price: {
                        discountedPrice: 14.99,
                        oldPrice: 29.99
                    }
                },
                {
                    id: 5,
                    firstImage: '/public/images/5.webp',
                    secondImage: '/public/images/5b.webp',
                    brand: 'Maya Deluxe',
                    productName: 'STRIPE BODICE',
                    price: {
                        discountedPrice: 99.99,
                    }
                },
                {
                    id: 6,
                    firstImage: '/public/images/6.webp',
                    secondImage: '/public/images/6b.webp',
                    specialTag: 'Sostenibilità',
                    brand: 'Esprit',
                    productName: 'MAGLIONE-BLACK',
                    price: {
                        discountedPrice: 29.99,
                    }
                }
            ]
        }
    }
}
</script>

<template>
    <main class="site-main">
        <div class="container d-flex-wrap">
            <ProductCard :product="product" v-for="product in products" />
        </div>
    </main>
</template>

<style></style>