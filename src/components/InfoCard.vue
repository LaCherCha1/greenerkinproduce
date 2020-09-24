<template>
	<div class="card h-100 border-0">
		<img :src="image" width="300px" class="card-img-top img-fluid d-block mx-auto" :alt="title" />
		<div class="card-body">
			<h5 class="card-title">{{ title }}</h5>
			<p class="card-text text-muted">
				<slot></slot>
			</p>
		</div>
	</div>
</template>

<script>
export default {
	name: "ReadMoreCard",
	props: {
		title: {
			type: String,
			required: true,
		},
		image: {
			type: String,
			required: true,
		},
		link: {
			type: String,
			required: false,
		},
	},
};
</script>

<style scoped>
img{
	width:300px;
	height: 200px;
}
</style>
