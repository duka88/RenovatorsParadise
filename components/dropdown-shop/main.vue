<template>
   <div class="dropdown dropdown--shop">
            <div class="dropdown__top">
                <div class="dropdown__wrap">
                    <div class="dropdown__btn-wrap">
                        <button class="dropdown__button" type="button">
                            <svg class="dropdown__form-icon-arrow">
                                <use xlink:href="~/assets/svg/sprite.svg#left-long-solid"></use>
                            </svg>
                            shop all
                        </button>
                        <span class="dropdown__close" aria-hidden="true"></span>
                    </div>
                </div>
            </div>
            <div class="dropdown__bottom">
                <div class="dropdown__wrap">
                     <ul class="dropdown__list">
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">RECYCLED TIMBER</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">DOORS</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">WINDOWS</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">MANTLES & FIRE GRATES</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'dropdown-shop'
}
</script>