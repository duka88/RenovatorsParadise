<template>
    <header class="header">
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
