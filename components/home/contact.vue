<template>
    <div class="contact">
      <div class="contact__inner">
          <div class="contact__item">
           <!-- <ContactItem svg="~/assets/svg/sprite.svg#location-dot-solid"/> -->
          </div>
          <div class="contact__item">

          </div>
          <div class="contact__item">

          </div>
      </div>
    </div>
</template>

<script>
import ContactItem from "@/components/contact-item/main.vue";

export default {
  name: 'contact',
  components: {
      ContactItem
  }
}
</script>