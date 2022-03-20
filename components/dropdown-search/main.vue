<template>
   <div class="dropdown dropdown--search">
            <div class="dropdown__top">
                <div class="dropdown__wrap">
                    <div class="dropdown__btn-wrap">
                        <button class="dropdown__button" type="button">Search</button>
                        <span class="dropdown__close" aria-hidden="true"></span>
                    </div>
                </div>
            </div>
            <div class="dropdown__bottom">
                <div class="dropdown__wrap">
                    <form class="dropdown__form" action="">
                        <input class="dropdown__input" type="text" placeholder="Search.." name="search">
                        <button class="dropdown__form-btn" type="submit">
                            <svg class="dropdown__form-icon">
                                <use xlink:href="~/assets/svg/sprite.svg#magnifying-glass-solid"></use>
                            </svg>
                        </button>
                    </form>
                    <div class="dropdown__text">
                        or use
                    </div>
                    <form class="dropdown__form dropdown__form--diff">
                        <input class="dropdown__input" type="text" placeholder="Product finder" name="search">
                        <button class="dropdown__form-btn" type="submit">
                            <svg class="dropdown__form-icon">
                                <use xlink:href="~/assets/svg/sprite.svg#magnifying-glass-solid"></use>
                            </svg>
                        </button>
                    </form>
                    <div class="dropdown__accordion">
                        <button class="dropdown__acc-item" type="button">
                            <span class="dropdown__acc-text">Category</span>
                            <svg class="dropdown__acc-icon">
                                <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                            </svg>
                        </button>
                        <button class="dropdown__acc-item" type="button">
                            <span class="dropdown__acc-text">Product</span>
                            <svg class="dropdown__acc-icon">
                                <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                            </svg>
                        </button>
                        <button class="dropdown__acc-item" type="button">
                            <span class="dropdown__acc-text">Type</span>
                            <svg class="dropdown__acc-icon">
                                <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: "dropdown-search"
};
</script>