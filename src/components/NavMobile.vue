<template>
	<div class="container-fluid">
		<nav v-if="!mobileView" class="header-nav">
			<a href="#"> 
				<img src="../assets/Logo.svg" alt="Productly">
			</a>
			<ul class="navbar">
				<li><a href="">Product</a></li>
				<li><a href="">Customers</a></li>
				<li><a href="">Pricing</a></li>
				<li><a href="">Resources</a></li>
			</ul>
			<div class="nav-buttons">
				<a href=""> Sign In</a>
				<a href=""> Sign Up</a>
			</div>
		</nav>
		<div v-if="mobileView" class="">
			<i class="fas fa-bars"></i>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Nav Mobile'
}
</script>

<style scoped>

</style>