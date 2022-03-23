<template>
    <section class="product-section">
        <div class="wrap">
            <div class="product-section__wrap">
                <ProductSlider />
                <div class="product-section__inner">
                    <h3 class="product-section__title">Recycled Timber Mantle
                        <span class="product-section__info">new</span>
                    </h3>
                    <div class="product-section__tags">
                        <span class="product-section__tag">stock</span>
                        <span class="product-section__tag">#F287</span>
                    </div>
                    <span class="product-section__price">$375.00</span>
                    <p class="product-section__nums">1285 mm width x 1780h mm height</p>
                    <p class="product-section__text">Recycled timber mantle from Sandringham home. Hardwood timber that’s been painted white. Hole size – 915 w x 915 h Top shelf – 1360 w</p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import ProductSlider from "@/components/product-slider/main.vue";

export default {
  name: 'product-section',
  components: {
      ProductSlider
  }
}
</script>