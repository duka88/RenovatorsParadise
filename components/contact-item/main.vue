<template>
    <div class="contact-item">
       <!-- {{title}} -->
        <svg>
          <use xlink:href="~/assets/svg/sprite.svg#bars-solid"></use>
        </svg>
    </div>
</template>

<script>
export default {
  name: 'contact-item',
  props: ['svg']
}
</script>