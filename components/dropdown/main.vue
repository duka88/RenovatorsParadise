<template>
   <div class="dropdown">
            <div class="dropdown__top">
                <div class="dropdown__wrap">
                    <div class="dropdown__btn-wrap">
                        <button class="dropdown__button" type="button">MAIN MENU</button>
                        <span class="dropdown__close" aria-hidden="true"></span>
                    </div>
                </div>
            </div>
            <div class="dropdown__bottom">
                <div class="dropdown__wrap">
                     <ul class="dropdown__list">
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">shop all</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">NEW IN</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">CUSTOM MADE</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/"></a>
                            <span class="dropdown__item-text">CUSTOM MADE</span>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                         <li class="dropdown__item dropdown__item--diff">
                            <a class="dropdown__link" href="/">
                            </a>
                            <span class="dropdown__item-text">CLEARANCE</span>
                            <span class="dropdown__link-small">Save up to 50%</span>
                        </li>
                        <li class="dropdown__item dropdown__item--small">
                            <a class="dropdown__link" href="/">
                            </a>
                            <span class="dropdown__link-text">DELIVERY</span>
                            <svg class="dropdown__icon">
                                <use xlink:href="~/assets/svg/sprite.svg#truck-fast-solid"></use>
                            </svg>
                        </li>
                        <li class="dropdown__item dropdown__item--small">
                            <a class="dropdown__link" href="/">
                            </a>
                            <span class="dropdown__link-text">SELLERS</span>
                            <svg class="dropdown__icon">
                                <use xlink:href="~/assets/svg/sprite.svg#handshake-solid"></use>
                            </svg>
                        </li>
                        <li class="dropdown__item dropdown__item--small">
                            <a class="dropdown__link" href="/">
                            </a>
                            <span class="dropdown__link-text">REFFERALS</span>
                            <svg class="dropdown__icon">
                                <use xlink:href="~/assets/svg/sprite.svg#user-group-solid"></use>
                            </svg>
                        </li>
                    </ul>
                    <div class="dropdown__cards">
                        <a class="dropdown__card" href="/">
                            <div class="dropdown__card-inner">
                                <svg class="dropdown__card-icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#user-solid"></use>
                                </svg>
                                <span class="dropdown__card-text">My Account</span>
                            </div>
                        </a>
                        <a class="dropdown__card" href="/">
                            <div class="dropdown__card-inner">
                                <svg class="dropdown__card-icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#clock-solid"></use>
                                </svg>
                                <span class="dropdown__card-text">Opening hours</span>
                            </div>
                        </a>
                        <a class="dropdown__card" href="/">
                            <div class="dropdown__card-inner">
                                <svg class="dropdown__card-icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#location-dot-solid"></use>
                                </svg>
                                <span class="dropdown__card-text">Visit our Showroom</span>
                            </div>
                        </a>
                        <a class="dropdown__card" href="tel:0370026570">
                            <div class="dropdown__card-inner">
                                <svg class="dropdown__card-icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#phone-solid"></use>
                                </svg>
                                <span class="dropdown__card-text">03 7002 6570</span>
                            </div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'dropdown'
}
</script>