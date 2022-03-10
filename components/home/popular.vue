<template>
    <section class="popular">
        <div class="wrap">
            <h2 class="popular__heading section-title">POPULAR CATEGORIES</h2>
            <div class="popular__items">
                <ShopItem title="RECYCLED TIMBER" />
                <ShopItem title="DOORS" />
                <ShopItem title="WINDOWS" />
                <ShopItem title="MANTLES & FIRE GRATES" />
                <ShopItem title="LIGHTING" />
                <ShopItem title="HARDWARE" />
            </div>
        </div>
    </section>
</template>

<script>
        
import ShopItem from "@/components/shop-item/main.vue";

export default {
  name: 'popular',
  components: {
        ShopItem
    }
}
</script>