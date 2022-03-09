<template>
	<div>
		<Hero />
		<Banner />
		<Popular />
		<Description />
	</div>
</template>

<script>
	import Hero from "@/components/home/hero.vue";
	import Banner from "@/components/home/banner.vue";
	import Description from "@/components/home/description.vue";
	import Popular from "@/components/home/popular.vue";
	export default {
		name: "IndexPage",
		components: {
			Hero,
			Banner,
			Description,
			Popular
		}
	};
</script>
