<template>
	<section class="banner banner--center">
		<div class="baner-center__wrap">
			<div class="banner-center__inner">
				<h2 class="banner-center__heading">{{title}}</h2>
				<p class="banner-center__text">{{text}}</p>
			</div>
		</div>
	</section>
</template>

<script>
	export default {
		name: "banner-center",
  		props: ['title', 'text'],
	};
</script>
