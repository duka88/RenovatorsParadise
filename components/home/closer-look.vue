<template>
	<section class="closer-look">
		<div class="wrap">
            <div class="closer-look__title section-title">TAKE A CLOSER LOOK</div>
			<div class="closer-look__inner">
				<ImageItem />
				<ImageItem />
				<ImageItem />
				<ImageItem />
				<ImageItem />
				<ImageItem />
			</div>
		</div>
	</section>
</template>

<script>
import ImageItem from "@/components/image-item/main.vue";

	export default {
		name: "closer-look",
        components: {
            ImageItem
        }
	};
</script>
