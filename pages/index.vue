<template>
	<main class="main">
		<Hero />
		<Banner />
		<Popular />
		<ShopAll />
		<Description />
		<NewIn title="FEATURED PRODUCTS" />
		<BannerRight />
		<NewIn title="NEW IN" />
		<TwoImg />
		<Contact />
		<ScrollUp />
	</main>
</template>

<script>
	import Hero from "@/components/home/hero.vue";
	import Banner from "@/components/home/banner.vue";
	import Description from "@/components/home/description.vue";
	import Popular from "@/components/home/popular.vue";
	import ShopAll from "@/components/home/shop-all.vue";
	import BannerRight from "@/components/home/banner-right.vue";
	import Contact from "@/components/home/contact.vue";
	import ScrollUp from "@/components/scroll-up/main.vue";
	import TwoImg from "@/components/home/two-img.vue";
	import NewIn from "@/components/home/new-in.vue";
	export default {
		name: "IndexPage",
		components: {
			Hero,
			Banner,
			Description,
			Popular,
			ShopAll,
			BannerRight,
			Contact,
			TwoImg,
			ScrollUp,
			NewIn
		}
	};
</script>
