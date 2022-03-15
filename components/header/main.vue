<template>
    <header class="header">
        <div class="dropdown">
            <div class="dropdown__top">
                <div class="wrap">
                    <div class="dropdown__btn-wrap">
                        <button class="dropdown__button" type="button">MAIN MENU</button>
                        <span class="dropdown__close" aria-hidden="true"></span>
                    </div>
                </div>
            </div>
            <div class="dropdown__bottom">
                <div class="wrap">
                     <ul class="dropdown__list">
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/">SHOP ALL</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/">NEW IN</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/">CUSTOM MADE</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                        <li class="dropdown__item">
                            <a class="dropdown__link" href="/">SHOP ALL</a>
                            <div class="dropdown__link-overlay" role="presentation"></div>
                        </li>
                         <li class="dropdown__item dropdown__item--diff">
                            <a class="dropdown__link" href="/">
                                CLEARANCE
                                <span class="dropdown__link-small">Save up to 50%</span>
                            </a>
                        </li>
                        <li class="dropdown__item dropdown__item--small">
                            <a class="dropdown__link" href="/">
                                <span class="dropdown__link-text">DELIVERY</span>
                                <svg class="dropdown__icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#truck-fast-solid"></use>
                                </svg>
                            </a>
                        </li>
                        <li class="dropdown__item dropdown__item--small">
                            <a class="dropdown__link" href="/">
                                <span class="dropdown__link-text">SELLERS</span>
                                <svg class="dropdown__icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#handshake-solid"></use>
                                </svg>
                            </a>
                        </li>
                        <li class="dropdown__item dropdown__item--small">
                            <a class="dropdown__link" href="/">
                                <span class="dropdown__link-text">REFFERALS</span>
                                <svg class="dropdown__icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#user-group-solid"></use>
                                </svg>
                            </a>
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
        <div class="header__top">
            <div class="wrap">
                <div class="header__top-inner">
                    <div class="header__phone-wrap">
                        <svg class="header__phone-icon">
                            <use xlink:href="~/assets/svg/sprite.svg#phone-solid"></use>
                        </svg>
                        <a class="header__phone" href="tel:(03)70026570">(03) 7002 6570</a>
                    </div>
                    <div class="header__text-wrap">
                        <p class="header__text">Melbourne's Largest Supplier of Quality     Recycled Building Materials
                        </p>
                    </div>
                    <nav class="nav">
                        <ul class="nav__list">
                            <li class="nav__item">
                                <a class="nav__link" href="/">Sign In / Register</a>
                            </li>
                            <li class="nav__item">
                                <a class="nav__link" href="/">Opening Hours</a>
                            </li>
                            <li class="nav__item">
                                <a class="nav__link" href="/">Contact</a>
                            </li>
                            <li class="nav__item">
                                <a class="nav__link" href="/">Wishlist</a>
                            </li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
        <div class="header__bottom">
            <div class="wrap">
               <div class="header__bottom-inner">
                    <div class="header__burger-nav-wrap">
                        <div class="header__burger-wrap">
                            <button class="header__burger" type="button">
                                <span class="sr-only">Burger menu</span>
                            </button>
                        </div>
                        <nav class="nav nav--header-bottom">
                            <ul class="nav__list">
                                <li class="nav__item">
                                    <a class="nav__link" href="/">SHOP ALL</a>
                                </li>
                                <li class="nav__item">
                                    <a class="nav__link" href="/">NEW IN</a>
                                </li>
                                <li class="nav__item">
                                    <a class="nav__link" href="/">CLEARANCE</a>
                                </li>
                                <li class="nav__item">
                                    <a class="nav__link" href="/">CUSTOM MADE</a>
                                </li>
                                <li class="nav__item">
                                    <a class="nav__link" href="/">SELLERS</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="header__logo-wrap">
                        <img class="header__logo" src="~/assets/img/RP_logo_white_transparent.png" alt="logo">
                    </div>
                    <div class="header__icons-wrap">
                        <svg class="header__icon header__icon--desk">
                            <use xlink:href="~/assets/svg/sprite.svg#location-dot-solid"></use>
                        </svg>
                        <span class="header__icon-text">VISIT OUR SHOWROOM</span>
                        <svg class="header__icon">
                            <use xlink:href="~/assets/svg/sprite.svg#magnifying-glass-solid"></use>
                        </svg>
                        <span class="header__icon-text">Search</span>
                        <svg class="header__icon">
                            <use xlink:href="~/assets/svg/sprite.svg#cart-shopping-solid"></use>
                        </svg>
                        <span class="header__icon-text">CART</span>
                   </div>
               </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
  name: "headerComponent"
};
</script>
