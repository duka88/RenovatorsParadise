<template>
    <section class="product-section">
        <div class="wrap wrap--small">
            <div class="product-section__wrap">
                <ProductSlider />
                <div class="product-section__inner">
                    <div class="product-section__text-wrap">
                        <h3 class="product-section__title">Recycled Timber Mantle
                        <span class="product-section__info">new</span>
                        </h3>
                        <div class="product-section__tags">
                            <span class="product-section__tag">stock</span>
                            <span class="product-section__tag">#F287</span>
                        </div>
                        <span class="product-section__price">$375.00</span>
                        <p class="product-section__nums">1285 mm width x 1780h mm height</p>
                        <ProductTable />
                        <p class="product-section__text">Recycled timber mantle from Sandringham home. Hardwood timber that’s been painted white. Hole size – 915 w x 915 h Top shelf – 1360 w</p>
                    </div>
                    <button class="btn btn--dark product-section__btn-first">
                        <svg class="product-section__icon">
                            <use xlink:href="~/assets/svg/sprite.svg#cart-shopping-solid"></use>
                        </svg>
                        Add to cart
                    </button>
                    <div class="product-section__btn-wrap">
                        <button class="btn btn--gray product-section__btn">
                            <svg class="product-section__icon">
                                <use xlink:href="~/assets/svg/sprite.svg#truck-fast-solid"></use>
                            </svg>
                            SHIPPING ESTIMATOR
                        </button>
                        <button class="btn btn--gray product-section__btn">
                             <svg class="product-section__icon">
                                <use xlink:href="~/assets/svg/sprite.svg#envelope-solid"></use>
                            </svg>
                            SEND ENQUIRY</button>
                    </div>
                    <svg class="product-section__small-icon">
                        <use xlink:href="~/assets/svg/sprite.svg#heart-solid"></use>
                    </svg>
                    <span class="product-section__small-text">Add to Wishlist</span>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import ProductSlider from "@/components/product-slider/main.vue";
import ProductTable from "@/components/product-table/main.vue";

export default {
  name: 'product-section',
  components: {
      ProductSlider,
      ProductTable
  }
}
</script>