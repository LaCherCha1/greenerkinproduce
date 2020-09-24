<template>
	<div class="main-top" :style="image" id="home">
		<slot></slot>
		<!-- banner -->
		<div class="main-banner text-center">
			<div class="container">
				<div class="style-banner">
					<h4 class="mb-2">
						Beyond just planting a seed… we contribute to a better future
					</h4>
					<h5>FOR OUR PEOPLE AND THE ENVIRONMENT</h5>
				</div>
			</div>
		</div>
	</div>
	<!-- //banner -->
</template>

<script>
export default {
	name: "MainTop",
	data() {
		return {
			image: {
				background: `url(${require("@/assets/images/b3.jpg")}) no-repeat bottom`,
				backgroundSize: "cover",
			},
		};
	},
};
</script>

<style scoped></style>
