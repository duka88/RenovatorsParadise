<template>
   <div class="dropdown dropdown-form">
            <div class="dropdown__top">
                <div class="dropdown__wrap">
                    <div class="dropdown__btn-wrap">
                        <button class="dropdown__button" type="button">ENQUIRY FORM</button>
                        <span class="dropdown__close" aria-hidden="true"></span>
                    </div>
                </div>
            </div>
            <div class="dropdown-form__bottom">
                <div class="dropdown__wrap">
                    <form class="dropdown-form__form" action="">
                        <div class="dropdown-form__flex">
                            <div class="dropdown-form__inputs">
                                <label class="dropdown-form__label" for="first-name">First Name
                                <span class="mandatory">*</span></label>
                                <input class="dropdown__input dropdown-form__input" type="text" name="first-name" id="first-name">
                            </div>
                            <div class="dropdown-form__inputs">
                                <label class="dropdown-form__label" for="last-name">Last Name
                                <span class="mandatory">*</span></label>
                                <input class="dropdown__input dropdown-form__input" type="text" name="last-name" id="last-name">
                            </div>
                        </div>
                        <div class="dropdown-form__inputs">
                            <label class="dropdown-form__label" for="email">Email
                            <span class="mandatory">*</span></label>
                            <input class="dropdown__input dropdown-form__input" type="text" name="email" id="email">
                        </div>
                        <div class="dropdown-form__flex">
                            <div class="dropdown-form__inputs">
                                <label class="dropdown-form__label" for="number">Phone number
                                <span class="mandatory">*</span></label>
                                <input class="dropdown__input dropdown-form__input" type="text" name="number" id="number">
                            </div>
                            <div class="dropdown-form__inputs">
                                <label class="dropdown-form__label" for="number">State
                                <span class="mandatory">*</span></label>
                                <select class="dropdown-form__select">
                                    <option value="0">Australia</option>
                                    <option value="1">2</option>
                                    <option value="2">3</option>
                                    <option value="3">4</option>
                                    <option value="4">5</option>
                                </select>
                                <!-- <svg class="dropdown-form__icon">
                                    <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                                </svg> -->
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: "dropdown-form"
};
</script>