<template>
	<div>
		<div class="mb-md-4 mb-3 mt-4">
			<i :class="icon" aria-hidden="true"></i>
		</div>
		<div>
			<h4 class="pb-3">{{title}}</h4>
			<p>
				<slot></slot>
			</p>
		</div>
	</div>
</template>

<script>
export default {
	name: "ServiceCard",
	props: {
		title: {
			type: String,
			required: true,
		},
		icon:{
			type: String,
			required:true
		}
	},
};
</script>

<style scoped>
i {
	font-size: 40px;
	color: #4c6248;
}
h4{
	font-size: 25px;
    color: #000000;
    text-transform: capitalize;
    font-weight: bold;
}
p{
	font-size: 14px;
    color: #4c4c4c;
	line-height: 25px;
	font-family: 'Mada', sans-serif;
}
</style>
