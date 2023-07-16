<script setup>
	import { colors,contact } from '../data/data'
</script>
<template>
	<section :style="contact.backgroundColor" class="mt-3">
		<div class="container pt-3">
			<h1 :style="contact.heading">Contact Us</h1>
		
			<div class="row g-0 pt-5">
			<div class=" col-sm-12 col-md-5">
				<table>
					<tr>
						<td><h1><i :class="contact.locationIcon" aria-hidden="true"></i></h1></td>
						<td><h5>&nbsp; A108 Adam Street, New York, NY 535022</h5></td>
					</tr> <br>
					<tr>
						<td><h1><i :class="contact.emailIcon" aria-hidden="true"></i></h1></td>
						<td><h5>&nbsp; info@example.com</h5></td>
					</tr> <br>
					<tr>
						<td><h1><i :class="contact.phoneIcon" aria-hidden="true"></i></h1></td>
						<td><h5>&nbsp; +1 5589 55488 55s</h5></td>
					</tr>
				</table>
			</div>
			<div class="col-sm-12 col-md-7">
				
					<form action="">
						<div class="mb-3">
							<label for="" class="form-label"><h3>Your Name</h3></label>
							<input type="text" class="form-control" id="" placeholder="Enter Your Name">
						</div>
						<div class="mb-3">
							<label for="" class="form-label"><h3>Subject</h3></label>
							<input type="text" class="form-control" id="" placeholder="Enter Your Subject">
						</div>
						<div class="mb-3">
							<label for="" class="form-label"><h3>Your Email</h3></label>
							<input type="email" class="form-control" id="" placeholder="Enter Your Email">
						</div>
						<div class="mb-3">
						<label for="" class="form-label"><h3>Message</h3></label>
						<textarea class="form-control" id="" rows="3"></textarea>
						</div>
						<div class="mb-3">
					
						<button :class="colors.primaryButton">Submit</button>
						</div>
					</form>
			
			</div>
		</div>
		</div>
	</section>
</template>
<style scoped></style>