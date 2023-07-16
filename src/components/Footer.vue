<script setup>
import {colors, footer } from '../data/data';
</script>
<template>
	<section>
		<div class="container-fluid" :style="footer.borderTop">
			<div class="details" :style="footer.center">
				<span>© Copyright LazyLand. All Rights Reserved</span>
				<h4>Develop by <b :class="colors.primaryColor">Sanjoy Kundu</b></h4>
			</div>
		</div>
	</section>
</template>
<style scoped></style>