<template>
    <section class="location">
        <div class="wrap">
            <div class="location__heading-wrap">
                <h2 class="location__heading">SHOWROOM</h2>
                <svg class="location__down-icon">
                    <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                </svg>
            </div>
            <div class="location-top">
                <svg class="location__icon">
                    <use xlink:href="~/assets/svg/sprite.svg#location-dot-solid"></use>
                </svg>
                <div class="location-top__wrap">
                    <h4 class="location-top__heading">
                        VISIT OUR SHOWROOM
                    </h4>
                    <p class="location-top__text">32 Futura Road Keysborough 3173</p>
                </div>
            </div>
            <div class="location__iframe"></div>
            <div class="location__heading-wrap">
                <h2 class="location__heading">shipping</h2>
                <svg class="location__down-icon">
                    <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                </svg>
            </div>
             <div class="location__bottom">
                <p class="location__text">We deliver to Melbourne and surrounding areas. Input your address and calculate shipping. The price allows for one delivery person and any number of items. Timber or Heavy items may incur an extra 20% fee. REGIONAL or INTERSTATE transport options are also listed on-click.</p>
                 <button class="btn btn--dark location__btn">
                    <svg class="location__icon">
                        <use xlink:href="~/assets/svg/sprite.svg#truck-fast-solid"></use>
                    </svg>
                    SHIPPING ESTIMATOR
                </button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'location'
}
</script>