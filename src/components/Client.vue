<script setup>
import { ourClient } from '../data/data'
</script>
<template>
	<section class="mt-5 mb-5">
		<div class="container p-5 mb-5">
			<div :style="ourClient.clientHeader">
				<h1>Our Clients</h1>
				<p :style="ourClient.p_size">Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.</p>
			</div>
			<div class="mt-5 pt-5">
				<div class="row row-cols-2 row-cols-md-4 g-4">
				<div class="col"><img :src="ourClient.clientImgOne" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgTwo" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgThree" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgFour" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgFive" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgSix" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgSeven" alt="" :class="ourClient.imgResponsive"></div>
				<div class="col"><img :src="ourClient.clientImgEight" alt="" :class="ourClient.imgResponsive"></div>
			</div>
			</div>
		</div>
	</section>
</template>
<style scoped></style>