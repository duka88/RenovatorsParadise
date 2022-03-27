<template>
  <main class="main">
    <BannerCenter  title="CUSTOM TIMBER JOINERY" text="Homepage / Custom" />
    <Description />
    <Custom />
    <Contact />
    <CloserLook />
    <Customers />
  </main>
</template>

<script>
import BannerCenter from "@/components/home/banner-center.vue";
import Description from "@/components/home/description.vue";
import Custom from "@/components/home/custom.vue";
import Contact from "@/components/home/contact.vue";
import CloserLook from "@/components/home/closer-look.vue";
import Customers from "@/components/home/customers.vue";

export default {

  name: 'CustomTimberJoiner',
  components: {
      BannerCenter,
      Description,
      Contact,
      Custom,
      CloserLook,
      Customers
		}
}
</script>
