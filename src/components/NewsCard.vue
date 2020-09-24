<template>
	<div class="card bg-dark text-white h-100 rounded-0">
		<a href="#" class="h-100">            
            <img :src="image" class="card-img h-100 rounded-0" alt="News" />            
            <div class="card-img-overlay--">			
                <p class="card-text text-white">
                    <slot></slot>
                </p>			
            </div>
        </a>
	</div>
</template>

<script>
export default {
	name: "NewsCard",
	props: {
        opacity:false,		
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
a:hover img {
  opacity: .5;
}
p{
    font-size: 1rem;
}
    div.card-img-overlay--{
    position: absolute;
    bottom: 0;
    left: 0;
    padding: 0.2rem 0.5rem;
    
    }
</style>
