<template>
	<div class="card border-0 h-100">
		<div class="card-body">
			<h5 class="card-title">{{ title }}</h5>
			<p class="card-text"><slot></slot></p>
		</div>
		<div class="card-footer bg-transparent text-center border-0">
			<a v-if="link" v-bind:href="link" class="btn btn-primary">Read more</a>
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
		link: {
			type: String,
			required: true,
		},
	},
};
</script>
