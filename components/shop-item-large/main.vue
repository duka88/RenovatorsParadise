<template>
    <div class="shop-item shop-item--large">
       <div class="shop-item__inner">
           <h3 class="shop-item__title">{{title}}</h3>
           <a class="shop-item__btn btn" href="/">Shop now</a>
       </div>
    </div>
</template>

<script>
export default {
  name: 'shop-item-large',
  props: ['title']
}
</script>