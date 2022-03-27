<template>
    <div class="custom-item">
      <div class="custom-item__inner">
          <p class="custom-item__text">{{title}}</p>
      </div>
    </div>
</template>

<script>
export default {
  name: 'custom-item',
  props: ['title']
}
</script>