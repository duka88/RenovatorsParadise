<template>
    <section class="shop-all popular">
        <div class="wrap">
            <h2 class="popular__heading section-title">Shop all</h2>
            <div class="popular__items">
                <ShopItemLarge title="BATHROOM & KITCHEN" />
                <ShopItemLarge title="HEATING & COOLING"/>
                <ShopItemLarge title="OUTDOOR PRODUCTS" />
                <ShopItemLarge title="FRETWORK & LACEWORK" />
                <ShopItemLarge title="SPECIALTY ITEMS" />
                <ShopItemLarge title="FURNITURE" />
            </div>
        </div>
    </section>
</template>

<script>
        
import ShopItemLarge from "@/components/shop-item-large/main.vue";

export default {
  name: 'shop-all',
  components: {
        ShopItemLarge
    }
}
</script>