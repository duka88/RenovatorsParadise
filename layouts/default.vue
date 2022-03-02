<template>
	<div>
		<Header />
		<!-- <svg>
			<use xlink:href="~/assets/svg/sprite.svg#bars-solid"></use>
		</svg>
    <img src="~/assets/img/article.jpg" alt=""> -->
		<nuxt />
		<Footer />
	</div>
</template>
<script>
	import Header from "@/components/header/main.vue";
	import Footer from "@/components/footer/main.vue";
	export default {
		components: {
			Header,
			Footer,
		},
	};
</script>
