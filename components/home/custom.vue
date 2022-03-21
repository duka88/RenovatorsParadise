<template>
	<section class="custom">
		<div class="wrap">
			<div class="custom__inner">
				<CustomItem />
				<CustomItem />
				<CustomItem />
				<CustomItem />
				<CustomItem />
				<CustomItem />
			</div>
		</div>
	</section>
</template>

<script>
import CustomItem from "@/components/custom-item/main.vue";

	export default {
		name: "custom",
        components: {
            CustomItem
        }
	};
</script>
