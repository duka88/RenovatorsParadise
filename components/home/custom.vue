<template>
	<section class="custom">
		<div class="wrap">
			<div class="custom__inner">
				<CustomItem title="CUSTOM BENCH SEAT" />
				<CustomItem title="CUSTOM BENCH TOPS" />
				<CustomItem title="CUSTOM TABLES" />
				<CustomItem title="CUSTOM BUILT BARN DOORS" />
				<CustomItem title="CUSTOM RUSTIC BARN DOORS" />
				<CustomItem title="BESPOKE FRONT DOORS" />
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
