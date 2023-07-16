<script setup>
	import { ourTeam } from '../data/data'
</script>
<template>
	<section class="mt-5 p-4" :style="ourTeam.backgroundColor">
		<div class="container pt-5">
				<div class="team-header" :style="ourTeam.teamHeader">
						<h1>Our Team</h1>
						<p :style="ourTeam.p_size">Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.</p>
				</div>
				<div class="row row-cols-1 row-cols-md-3 g-4 mt-5">
				<div class="col">
					<div class="card h-100">
					<img :src="ourTeam.imageOne" alt="">
					<div class="card-body">
						<h3 class="card-title">Name: Walter White</h3>
						<h5 class="card-text">Title: Chief Executive Officer</h5>
					</div>
					</div>
				</div>
		
				<div class="col">
					<div class="card h-100">
					<img :src="ourTeam.imageTwo" alt="">
					<div class="card-body">
						<h3 class="card-title">Name: Sarah Jhonson</h3>
						<h5 class="card-text">Title: Product Manager</h5>
					</div>
					</div>
				</div>
		
				<div class="col">
					<div class="card h-100">
					<img :src="ourTeam.imageThree" alt="">
					<div class="card-body">
						<h3 class="card-title">Name: William Anderson</h3>
						<h5 class="card-text">Title: Full Stack Software Enginner</h5>
					</div>
					</div>
				</div>
		
		
</div>
		</div>
	</section>
</template>
<style scoped></style>