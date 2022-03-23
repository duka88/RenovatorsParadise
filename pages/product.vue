<template>
  <main class="main main--product">
    <ProductSection />
    <NewIn title="WE ALSO RECOMMEND" />
    <NewIn title="YOU MAY ALSO LIKE" />
    <Contact />
  </main>
</template>

<script>
import Contact from "@/components/home/contact.vue";
import NewIn from "@/components/home/new-in.vue";
import ProductSection from "@/components/home/product-section.vue";

export default {

  name: 'Product',
  components: {
      Contact,
      NewIn,
      ProductSection
    }
}
</script>
