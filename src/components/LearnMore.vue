<script setup>
import {colors,learnMore} from '../data/data'
</script>
<template>
	<section class="container-fluid" :style="learnMore.backgroundColor">
		<div class="container" >
			<div class="row mt-5 p-2">
  				<div class="col-sm-12 col-md-6 mb-3 mb-sm-0 pt-4">
					<img :src="learnMore.image" alt="" :class="learnMore.imgResponsive">
				</div>
  				<div class="col-sm-12 col-md-6 mb-sm-0 pt-4">
				
					<h2 style="">Learn more about us</h2>
					<p :style="[colors.paragraphColor, learnMore.font_style, learnMore.font_size]">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
					<ul>
						 <li :style="[learnMore.list_style, learnMore.font_size,colors.paragraphColor]"> <i :class="learnMore.checkCircle"></i> Ullamco laboris nisi ut aliquip ex ea commodo consequat.</li> <br>
						 <li :style="[learnMore.list_style, learnMore.font_size,colors.paragraphColor]"> <i :class="learnMore.checkCircle"></i> Duis aute irure dolor in reprehenderit in voluptate velit.</li> <br>
						 <li :style="[learnMore.list_style, learnMore.font_size,colors.paragraphColor]"> <i :class="learnMore.checkCircle"></i>  Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate trideta storacalaperd</li> <br>
					</ul>
					<p :style="[learnMore.font_size, colors.paragraphColor]">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate tera noden carma palorp mades tera.</p>
					
				</div>
			</div>
		</div>
	</section>
</template>
<style scoped></style>