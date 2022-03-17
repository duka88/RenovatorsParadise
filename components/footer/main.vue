<template>
   <footer class="footer">
      <div class="wrap">
          <div class="footer-inner">
        <div class="footer-top">
            <!-- <svg class="footer-top__icon">
                <use xlink:href="~/assets/svg/sprite.svg#logo-white"></use>
            </svg> -->
             <img class="footer-top__logo" src="~/assets/img/logo-white.svg" alt="logo">
            <div class="footer-top__wrap">
                <h4 class="footer-top__heading">
                    VISIT OUR SHOWROOM
                </h4>
                <p class="footer-top__text">32 Futura Road Keysborough 3173</p>
            </div>
        </div>
         <div class="footer__wrap">
            <div class="footer__text-wrap">
                <h4 class="footer__heading" data-open="false">
                  <span class="footer__heading-text">INFORMATION</span>
                  <svg class="footer__icon">
                     <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                  </svg>
                </h4>
                <ul class="footer-nav__list">
                    <li class="footer-nav__item">
                      <a class="footer-nav__link" href="/">Delivery</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">Referrals</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">Sellers</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">About Us</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">Wishlist</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">My Account</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">Login</a>
                    </li>
                    <li class="footer-nav__item">
                        <a class="footer-nav__link" href="/">Contact</a>
                    </li>
                </ul>
            </div>
            <!-- <a href="tel:1300 898 560" class="footer__heading text-orange">P: 1300 898 560</a> -->
            <nav class="footer-nav" aria-label="Footer menu">
               <div class="footer-nav__menu">
                  <div class="footer-nav__item">
                     <h4 class="footer__heading" data-open="false">
                        <span class="footer__heading-text">PRODUCTS</span>
                        <svg class="footer__icon">
                           <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                        </svg>
                     </h4>
                     <ul class="footer-nav__list">
                        <li class="footer-nav__item">
                           <a class="footer-nav__link" href="/">Recycled Timber</a>
                        </li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Doors</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Windows</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Mantles and Grates</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Lighting</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Hardware</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Bathroom and Kitchen</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Heating and Cooling</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Furniture</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Fretwork and Lacework</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Outdoor Products</a></li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Speciality Items</a></li>
                     </ul>
                  </div>
                  <div class="footer-nav__item">
                     <h4 class="footer__heading  jsAccordian" data-open="false">
                        <span class="footer__heading-text">OPENING HOURS</span>
                        <svg class="footer__icon">
                           <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                        </svg>
                     </h4>
                     <ul class="footer-nav__list">
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">Monday to Friday: 8am - 5pm</a></li>
                        <li class="footer-nav__item">Saturday: 9am - 4:30pm</li>
                        <li class="footer-nav__item">Product Categories</li>
                        <li class="footer-nav__item">Closed Sunday and Public Holidays</li>
                     </ul>
                     <h4 class="footer__heading jsAccordian" data-open="false">
                        <span class="footer__heading-text">CONTACT US</span>
                        <svg class="footer__icon">
                           <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                        </svg>
                     </h4>
                     <ul class="footer-nav__list">
                        <li class="footer-nav__item"><a class="footer-nav__link" href="/">32 Futura Road</a></li>
                        <li class="footer-nav__item">Keysborough VIC 3173</li>
                        <li class="footer-nav__item"><a class="footer-nav__link" href="tel:(03)70026570">(03) 7002 6570</a></li>
                     </ul>
                  </div>
               </div>
            </nav>
            <div class="footer-form">
               <div class="footer-form__wrap">
                  <h4 class="footer__heading">SPECIAL OFFERS & NEWS</h4>
                  <form class="footer-form__form" method="post" action="" aria-label="Newsletter subscribe form">
                     <input type="hidden" name="csrf_token" value="">
                     <input type="hidden" name="list_id" value="1">
                     <input type="hidden" name="opt_in" value="y">
                     <input type="hidden" name="inp-submit" value="y">
                     <input type="hidden" name="inp-opt_in" value="y">
                     <div class="footer-form__input-wrap">
                        <input name="inp-email" class="footer-form__input" type="email" value="" placeholder="Enter your email address" required="" aria-label="Email Address">
                        <svg class="footer__icon footer__icon--mail">
                            <use xlink:href="~/assets/svg/sprite.svg#envelope-solid"></use>
                        </svg>
                        <button class="footer-form__btn" type="submit">
                            <svg class="footer__icon footer__icon--rotated">
                                <use xlink:href="~/assets/svg/sprite.svg#chevron-down-solid"></use>
                            </svg>
                        </button>
                     </div>
                  </form>
               </div>
                <ul class="footer-social">
               <li class="footer-social__item">
                   <a href="" target="_blank">
                   <svg class="footer-social__icon">
                       <use xlink:href="~/assets/svg/sprite.svg#instagram-brands"></use>
                   </svg>
                   </a>
               </li>
               <li class="footer-social__item">
                   <a href="" target="_blank">
                   <svg class="footer-social__icon">
                       <use xlink:href="~/assets/svg/sprite.svg#facebook-square-brands"></use>
                   </svg>
                   </a>
               </li>
               <li class="footer-social__item">
                   <a href="" target="_blank">
                   <svg class="footer-social__icon">
                       <use xlink:href="~/assets/svg/sprite.svg#youtube-brands"></use>
                   </svg>
                   </a>
               </li>
               </ul> 
            </div>
           
            
         </div>
         </div>
         <div class="footer-bottom">
               <ul class="footer-bottom__menu">
                   <li class="footer-bottom__menu-item">
                   <a href="/" data-toggle="modal" class="footer-bottom__text">Terms of Use</a>
                   </li>
                   <li class="footer-bottom__menu-item">
                   <a href="/" data-toggle="modal" class="footer-bottom__text">Terms of Sale</a>
                   </li>
                   <li class="footer-bottom__menu-item">
                   <a href="/" class="footer-bottom__text">Privacy Policy</a>
                   </li>
               </ul>
               <p class="footer-bottom__text">
                   Copyright © 2021 · Renovators Paradise 
               </p>
               </div> 
      </div>
   </footer>
</template>
<script>
export default {
  name: "footerComponent"
};
</script>