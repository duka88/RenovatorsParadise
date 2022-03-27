<template>
  <main class="main">
    <BannerCenter v-bind:style="{minHeight: 256 + 'px', paddingTop: 6 + 'vh', paddingBottom: 6 + 'vh'}" title="Doors" text="Homepage / Doors" />
    <div class="wrap">
      <div class="custom-wrap">
        <p class="custom-wrap__text">We have Australia’s largest selection of quality recycled doors. These are all  available to view online and complete with photos, sizes and prices. Select one of the categories below to view our entire range.</p>
        <div class="custom-wrap__inner">
          <CustomItem title="FRONT ENTRANCE WAYS" />
          <CustomItem title="DOORS & EXTERNAL FRAMES"/>
          <CustomItem title="SINGLE FRONT DOORS" />
          <CustomItem title="DOUBLE FRONT DOORS" />
          <CustomItem title="LEDGE BRACE DOORS" />
          <CustomItem title="SECURITY DOORS" />
          <CustomItem title="DOUBLE DOORS" />
          <CustomItem title="SINGLE FULL GLASS" />
          <CustomItem title="SINGLE SOLID PANEL" />
          <CustomItem title="SINGLE PART GLASS" />
          <CustomItem title="CUPBOARD & LOUVRE" />
          <CustomItem title="INTERNAL BI-FOLDING" />
        </div>
        <div class="filter">
         <div class="filter__part filter__part--first">
            <span class="filter__text">Filters</span>
            <button class="filter__mob-btn filter__mob-btn--diff" type="button">
               <svg class="filter__icon">
                    <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                </svg>
                <span>Filters</span>
            </button>
            <ul class="filter__list">
              <li class="filter__item">
                <button class="filter__btn" type="button">
                  Material
                  <svg class="filter__icon">
                        <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                    </svg>
                </button>
              </li>
               <li class="filter__item">
                <button class="filter__btn" type="button">
                  Height
                  <svg class="filter__icon">
                        <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                    </svg>
                </button>
              </li>
               <li class="filter__item">
                <button class="filter__btn" type="button">
                  Width
                  <svg class="filter__icon">
                        <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                    </svg>
                </button>
              </li>
               <li class="filter__item">
                <button class="filter__btn" type="button">
                  Indoor / Outdoor
                  <svg class="filter__icon">
                        <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                    </svg>
                </button>
              </li>
               <li class="filter__item">
                <button class="filter__btn" type="button">
                  Price Range
                  <svg class="filter__icon">
                        <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                    </svg>
                </button>
              </li>
            </ul>
          </div>
          <div class="filter__part filter__part--second">
            <span class="filter__text">Sort by</span>
              <button class="filter__btn filter__mob-btn" type="button">
                <span>Default</span>
                <svg class="filter__icon">
                      <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                  </svg>
              </button>
          </div>

        </div>
      </div>
   </div>
    <div class="buy-item-wrap">
      <div class="buy-item-wrap__inner">
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
          <BuyItem />
      </div>
    </div>
    <Contact />
  </main>
</template>

<script>
import BannerCenter from "@/components/home/banner-center.vue";
import CustomItem from "@/components/custom-item/main.vue";
import Contact from "@/components/home/contact.vue";
import BuyItem from "@/components/buy-item/main.vue";

export default {
  name: 'Category',
  components: {
    BannerCenter,
    CustomItem,
    Contact,
    BuyItem
  }
}
</script>
