<template>
  <main class="main">
    <BannerCenter />
    <Description />
    <Custom />
    <Contact />
    <CloserLook />
  </main>
</template>

<script>
import BannerCenter from "@/components/home/banner-center.vue";
import Description from "@/components/home/description.vue";
import Custom from "@/components/home/custom.vue";
import Contact from "@/components/home/contact.vue";
import CloserLook from "@/components/home/closer-look.vue";

export default {

  name: 'CustomTimberJoiner',
  components: {
      BannerCenter,
      Description,
      Contact,
      Custom,
      CloserLook
		}
}
</script>
