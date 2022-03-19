<template>
    <div class="buy-item">
       <div class="buy-item__inner">
            <div class="buy-item__tag-wrap">
                <span class="buy-item__tag">sale</span>
                <img class="buy-item__tag-img" src="~/assets/img/hearth.svg" alt="Shop item">
            </div>
            <div class="buy-item__img-wrap">
                <img class="buy-item__img" src="~/assets/img/buy-item.png" alt="Shop item">
                <a class="buy-item__btn btn" href="/">Enquire / buy</a>
            </div>
            <span class="buy-item__hash"># F865</span>
            <h3 class="buy-item__title">Flemington Members Bar Door</h3>
            <p class="buy-item__num">945w x 2145h</p>
            <div class="buy-item__price-wrap">
                <span class="buy-item__sale">$950.00</span>
                <span class="buy-item__price">$1,250.00</span>
            </div>
       </div>
    </div>
</template>

<script>
export default {
  name: 'buy-item',
  props: ['title'],
}
</script>