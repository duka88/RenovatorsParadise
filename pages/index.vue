<template>
	<div>
		<Hero />
		<Banner />
		<Popular />
		<ShopAll />
		<Description />
		<BannerRight />
	</div>
</template>

<script>
	import Hero from "@/components/home/hero.vue";
	import Banner from "@/components/home/banner.vue";
	import Description from "@/components/home/description.vue";
	import Popular from "@/components/home/popular.vue";
	import ShopAll from "@/components/home/shop-all.vue";
	import BannerRight from "@/components/home/banner-right.vue";
	export default {
		name: "IndexPage",
		components: {
			Hero,
			Banner,
			Description,
			Popular,
			ShopAll,
			BannerRight
		}
	};
</script>
