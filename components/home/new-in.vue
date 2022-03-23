<template>
    <section class="new-in">
        <div class="wrap">
            <h2 class="new-in__title section-title">{{title}}</h2>
            <div class="new-in__inner">
                <BuyItem />
                <BuyItem />
                <BuyItem />
                <BuyItem />
                <BuyItem />
            </div>
        </div>
    </section>
</template>

<script>

import BuyItem from "@/components/buy-item/main.vue";

export default {
  name: 'NewIn',
  props: ['title'],
  components: {
        BuyItem
    }
}
</script>