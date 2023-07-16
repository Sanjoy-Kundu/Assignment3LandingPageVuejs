<script setup>
	import { services } from '../data/data'
</script>
<template>
	<section class="container mt-5">
		<div class="title pt-5">
			<h1 :class="[services.titleHeadingCenter]" :style="[services.titleColor, services.titleFontSize]">Services</h1>
			<p :style="services.p_size, services.titleHeadingCenter,services.titleColor">Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.</p>
		</div>

	<div class="row row-cols-1 row-cols-md-4 g-4 p-5">
			<div class="col">
				<div class="card h-100">
					<h4 :class="services.titleHeadingCenter"><i :class="services.cardIconOne" :style="services.cartIconSize"></i></h4>
				<div class="card-body">
					<h4 :class="services.cartTitle">Service One</h4>
					<p :class="services.cartP" :style="[services.cartFontSize, services.cardFontBold]">Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate</p>
				</div>
				</div>
			</div>
			<div class="col">
				<div class="card h-100">
					<h4 :class="services.titleHeadingCenter"><i :class="services.cardIconTwo" :style="services.cartIconSize"></i></h4>
					<div class="card-body">
					<h4 :class="services.cartTitle">Service Two</h4>
					<p :class="services.cartP" :style="[services.cartFontSize, services.cardFontBold]">Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate</p>
				</div>
				</div>
			</div>
			<div class="col">
				<div class="card h-100">
					<h4 :class="services.titleHeadingCenter"><i :class="services.cardIconThree" :style="services.cartIconSize"></i></h4>
					<div class="card-body">
					<h4 :class="services.cartTitle">Service Three</h4>
					<p :class="services.cartP" :style="[services.cartFontSize, services.cardFontBold]">Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate</p>
				</div>
				</div>
			</div>
			<div class="col">
				<div class="card h-100">
					<h4 :class="services.titleHeadingCenter"><i :class="services.cardIconFour" :style="services.cartIconSize"></i></h4>
					<div class="card-body">
					<h4 :class="services.cartTitle">Service Four</h4>
					<p :class="services.cartP" :style="[services.cartFontSize, services.cardFontBold]">Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate</p>
				</div>
				</div>
			</div>
		</div>

	</section>
</template>
<style scoped></style>