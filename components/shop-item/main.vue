<template>
    <div class="shop-item">
       <div class="shop-item__inner">
           <h3 class="shop-item__title">{{title}}</h3>
           <a class="shop-item__btn btn" href="/">Shop now</a>
       </div>
    </div>
</template>

<script>
export default {
  name: 'shop-item',
  props: ['title'],
}
</script>