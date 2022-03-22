<template>
	<section class="customers">
		<div class="wrap">
            <h2 class="customers__title section-title">OUR SATISFIED CUSTOMERS</h2>
			<div class="customers__inner">
				<Customer />
				<Customer />
				<Customer />
				<Customer />
				<Customer />
			</div>
		</div>
	</section>
</template>

<script>
import Customer from "@/components/customer/main.vue";

	export default {
		name: "custom",
        components: {
            Customer
        }
	};
</script>
