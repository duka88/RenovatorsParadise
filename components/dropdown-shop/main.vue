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
                            <a class="dropdown__link" href="/">RECYCLED TIMBER</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/">DOORS</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/">WINDOWS</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item dropdown__item--thin">
                            <a class="dropdown__link" href="/">MANTLES & FIRE GRATES</a>
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