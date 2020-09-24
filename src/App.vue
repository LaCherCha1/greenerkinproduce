<template>
	<main>
		<MainTop>
			<MainMenu></MainMenu>
		</MainTop>
		<!-- read more  -->
		<section class="container bg-white py-5">
			<div class="row">
				<div class="col-12 col-lg-4">
					<ReadMoreCard title="About Us" link="hola">
						Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reprehenderit
						debitis molestiae excepturi vitae blanditiis cum vero ipsum aliquam pariatur
						quis cupiditate culpa libero maiores ad rem optio voluptates modi, fugiat,
						mollitia dolorem nihil deleniti alias! Cum numquam non magnam. Mollitia
						ullam a quidem distinctio ducimus assumenda repellat aperiam error sed?
					</ReadMoreCard>
				</div>
				<div class="col-12 col-lg-4">
					<ReadMoreCard title="History" link="hola">
						Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quae, assumenda
						obcaecati qui, odit saepe quas perferendis eveniet, eos ad nemo eaque
						corrupti commodi. Nisi, dolorem!
					</ReadMoreCard>
				</div>
				<div class="col-12 col-lg-4">
					<ReadMoreCard title="Responsability" link="hola">
						Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur
						obcaecati quae accusamus delectus maxime, sequi rerum animi? Illum, vitae
						similique amet veniam nobis possimus! Inventore dicta aliquid dolorem. Ex,
						cupiditate?
					</ReadMoreCard>
				</div>
			</div>
		</section>
		<!-- /read more -->
		<!-- info  -->
		<section class="container-fluid bg-light py-5">
			<div class="container">
				<div class="row">
					<div class="col-xs-12 col-sm-6 col-lg-3 my-3">
						<InfoCard
							title="Our People"
							image="https://images.unsplash.com/photo-1559884743-74a57598c6c7?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1510&q=80"
						>
							Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quaerat,
							voluptas?
						</InfoCard>
					</div>
					<div class="col-xs-12 col-sm-6 col-lg-3 my-3">
						<InfoCard
							title="Community Development"
							image="https://images.unsplash.com/photo-1596133202325-fc6d5299b3a0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
						>
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi, ipsum.
						</InfoCard>
					</div>
					<div class="col-xs-12 col-sm-6 col-lg-3 my-3">
						<InfoCard
							title="Environment"
							image="https://images.unsplash.com/photo-1594117782204-5c398aa0e330?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=80"
						>
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate,
							commodi.
						</InfoCard>
					</div>
					<div class="col-xs-12 col-sm-6 col-lg-3 my-3">
						<InfoCard
							title="Sustainability"
							image="https://images.unsplash.com/photo-1593819256510-9bbdd295374d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1267&q=80"
						>
							Lorem ipsum dolor sit amet consectetur adipisicing elit.
						</InfoCard>
					</div>
				</div>
			</div>
		</section>
		<!-- /info -->

		<!-- stats -->
		<section class="stats-count py-lg-4 py-md-3 py-sm-3 py-3" :style="statsImage">
			<div class="container-fluid py-lg-5 py-md-4 py-sm-4 py-3">
				<div class="row text-center">
					<div class="col-lg-3 col-md-3 col-sm-6 col-6 number-w3three-info">
						<span class="far fa-smile" data-blast="bgColor"></span>
						<h5>600</h5>
						<h6 class="pt-2">Happy Customers</h6>
					</div>
					<div class="col-lg-3 col-md-3 col-sm-6 col-6 number-w3three-info">
						<span class="fas fa-shield-alt" data-blast="bgColor"></span>
						<h5>350 +</h5>
						<h6 class="pt-2">Awards Win</h6>
					</div>
					<div class="col-lg-3 col-md-3 col-sm-6 col-6 number-w3three-info">
						<span class="fas fa-leaf" data-blast="bgColor"></span>
						<h5>250</h5>
						<h6 class="pt-2">Products</h6>
					</div>
					<div class="col-lg-3 col-md-3 col-sm-6 col-6 number-w3three-info">
						<span class="fas fa-thumbs-up" data-blast="bgColor"></span>
						<h5>225</h5>
						<h6 class="pt-2">Ratings</h6>
					</div>
				</div>
			</div>
		</section>
		<!--//stats -->

		<!-- Services -->
		<section class="py-lg-4 py-md-3 py-sm-3 py-3 bg-light">
			<div class="container py-lg-5 py-md-4 py-sm-4 py-3">
				<h3 class="title text-center mb-lg-5 mb-md-4 mb-sm-4 mb-3">
					Our Services
				</h3>
				<div class="row">
					<div class="col-lg-4 col-md-6 col-sm-6 text-center">
						<ServiceCard title="Garden Care" icon="fab fa-apple"
							>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit,
							ea.</ServiceCard
						>
					</div>
					<div class="col-lg-4 col-md-6 col-sm-6 text-center">
						<ServiceCard title="Plant Renovation" icon="fab fa-yelp"
							>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit,
							ea.</ServiceCard
						>
					</div>
					<div class="col-lg-4 col-md-6 col-sm-6 text-center">
						<ServiceCard title="Quality Products" icon="fab fa-viadeo"
							>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit,
							ea.</ServiceCard
						>
					</div>
					<div class="col-lg-4 col-md-6 col-sm-6 text-center">
						<ServiceCard title="Always Fresh" icon="fas fa-leaf"
							>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit,
							ea.</ServiceCard
						>
					</div>
					<div class="col-lg-4 col-md-6 col-sm-6 text-center">
						<ServiceCard title="Transportation" icon="fas fa-dolly-flatbed"
							>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit,
							ea.</ServiceCard
						>
					</div>
					<div class="col-lg-4 col-md-6 col-sm-6 text-center">
						<ServiceCard title="Alliances" icon="fab fa-skyatlas"
							>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit,
							ea.</ServiceCard
						>
					</div>
				</div>
			</div>
		</section>
		<!-- /Services -->
		<!-- News -->
		<section class="mt-4">
			<div class="container-fluid p-0">
				<h3 class="title text-center mb-lg-5 mb-md-4 mb-sm-4 mb-3">
					Lastest News
				</h3>
				<div class="row m-0">
					<div class="col-12 col-md-6 p-0">
						<NewsCard image="https://picsum.photos/id/305/575/284">
							Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum, sit.
						</NewsCard>
					</div>
					<div class="col-12 col-md-6 p-0">
						<div class="row h-100 w-100 m-0">
							<div class="col-12 col-md-6 p-0">
								<NewsCard image="https://picsum.photos/id/310/305/140">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum,
									sit.
								</NewsCard>
							</div>
							<div class="col-12 col-md-6 p-0">
								<NewsCard image="https://picsum.photos/id/308/305/140">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum,
									sit.
								</NewsCard>
							</div>
							<div class="col-12 col-md-6 p-0">
								<NewsCard image="https://picsum.photos/id/307/305/140">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum,
									sit.
								</NewsCard>
							</div>
							<div class="col-12 col-md-6 p-0">
								<NewsCard image="https://picsum.photos/id/309/305/140">
									Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum,
									sit.
								</NewsCard>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>
		<!-- //News -->

		<!-- footer -->
		<footer class="py-lg-4 py-md-3 py-sm-3 py-3">
			<div class="container py-lg-5 py-md-5 py-sm-4 py-3">
				<div class="footer-w3layouts-head text-center">
					<h2><a href="index.html">GreenerKinProduce</a></h2>
				</div>
				<div class="social-icons mt-lg-5 mt-md-4 mt-3 text-center">
					<ul>
						<li>
							<a href="#"><span class="fab fa-facebook-f"></span></a>
						</li>
						<li>
							<a href="#"><span class="fab fa-twitter"></span></a>
						</li>
						<li>
							<a href="#"><span class="fas fa-envelope"></span></a>
						</li>
						<li>
							<a href="#"><span class="fab fa-instagram"></span></a>
						</li>
					</ul>
				</div>
				<div class="bottem-wthree-footer text-center pt-md-4 pt-3">
					<p>© 2020 {{ titulo }}. All Rights Reserved</p>
				</div>
				<!-- move icon -->
				<div class="text-center">
					<a href="#home" class="move-top text-center mt-3"
						><i class="fa fa-arrow-up" aria-hidden="true"></i
					></a>
				</div>
				<!--//move icon -->
			</div>
		</footer>
		<!--//footer -->
	</main>
</template>

<script>
import MainMenu from "@/components/MainMenu";
import MainTop from "@/components/MainTop";
import ReadMoreCard from "@/components/ReadMoreCard";
import InfoCard from "@/components/InfoCard";
import ServiceCard from "@/components/ServiceCard";
import NewsCard from "@/components/NewsCard";

export default {
	name: "App",
	data() {
		return {
			titulo: "GreenerKinProduce",
			statsImage: {
				background: `url(${require("@/assets/images/b2.jpg")}) no-repeat center`,
				backgroundSize: "cover",
			},
		};
	},
	components: {
		MainMenu,
		MainTop,
		ReadMoreCard,
		InfoCard,
		ServiceCard,
		NewsCard,
	},
};
</script>

<style>
@import url("./assets/css/style.css");
@import url("https://fonts.googleapis.com/css2?family=Mada:wght@300&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Mada:wght@300&family=Poiret+One&display=swap");

.title {
	color: #4c6248;
	letter-spacing: 2px;
	font-weight: 700;
	text-transform: capitalize;
}
.social-icons a {
	color: #6f6e6e;
	font-size: 29px;
	margin: 0px 22px;
	transition: 0.5s all;
	-webkit-transition: 0.5s all;
	transition: 0.5s all;
	-moz-transition: 0.5s all;
}
.social-icons a:hover {
	color: #fff;
}
.number-w3three-info svg {
	font-size: 30px;
	line-height: 2.1;
	border-radius: 5px;
	text-align: center;
	color: #fff;
}
</style>
