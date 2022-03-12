<template>
    <section class="contact">
        <div class="wrap">
            <div class="contact__inner">
                <div class="contact-item">
                <!-- <ContactItem svg="~/assets/svg/sprite.svg#location-dot-solid"/> -->
                    <div class="contact-item__inner">
                        <svg class="contact-item__icon">
                            <use xlink:href="~/assets/svg/sprite.svg#phone-solid"></use>
                        </svg>   
                        <h3 class="contact-item__title">Get In Touch</h3> 
                        <p class="contact-item__text">Pellentesque habitasse justo et nunc. Volutpat malesuada elementum, sem tincidunt mauris at. </p>
                        <a class="contact-item__link" href="/">Enquire Now</a>
                    </div> 
                </div>
                <div class="contact-item">
                    <div class="contact-item__inner">
                        <svg class="contact-item__icon">
                            <use xlink:href="~/assets/svg/sprite.svg#location-dot-solid"></use>
                        </svg>   
                        <h3 class="contact-item__title">Get In Touch</h3> 
                        <p class="contact-item__text">Pellentesque habitasse justo et nunc. Volutpat malesuada elementum, sem tincidunt mauris at. </p>
                        <a class="contact-item__link" href="/">Enquire Now</a>
                    </div> 
                </div>
                <div class="contact-item">
                    <div class="contact-item__inner">
                        <svg class="contact-item__icon">
                            <use xlink:href="~/assets/svg/sprite.svg#truck-fast-solid"></use>
                        </svg>   
                        <h3 class="contact-item__title">Get In Touch</h3> 
                        <p class="contact-item__text">Pellentesque habitasse justo et nunc. Volutpat malesuada elementum, sem tincidunt mauris at. </p>
                        <a class="contact-item__link" href="/">Enquire Now</a>
                    </div> 
                </div>
            </div>
        </div>
    </section>
</template>

<script>
// import ContactItem from "@/components/contact-item/main.vue";

export default {
  name: 'contact',
//   components: {
//       ContactItem
//   }
}
</script>