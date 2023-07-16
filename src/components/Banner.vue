<script setup>
	import {banner, colors}  from '../data/data'
</script>
<template>
	<section class="container-fluid">
		<div class="container">
			<div class="row mt-5">
  				<div class="col-sm-12 col-md-6 mb-3 mb-sm-0 pt-5">
					<h1 :style="colors.headingFrontSize">We design digital products that help grow businesses</h1>
					<p :style="[colors.paragraphColor, colors.paragraphSize]">We are team of talented designers making websites with Html, Css, Bootstrap</p>
					<button :class="colors.primaryButton">Get Started</button>
				</div>
  				<div class="col-sm-12 col-md-6 mb-sm-0">
					<img :src="banner.bannerImg" alt="" :class="banner.imgResponsive">
				</div>
			</div>
		</div>
	</section>
</template>
<style scoped></style>