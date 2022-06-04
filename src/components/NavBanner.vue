<template>
	<div class="container-fluid colorbg2">
		<div class="color2 name"> Alexander Naylor </div>
		<nav class="nav nav-tabs nav-fill">
			<router-link to="/" class="nav-link">About</router-link>
			<router-link to="/about" class="nav-link">Projects</router-link>
			<router-link to="/" class="nav-link">Contact</router-link>
		</nav>
	</div>
</template>

<style scoped>
	.name{
		font-size: 30pt;
	}

	.colorbg2{
		background-color: var(--colorbg2);
	}

	.active {
		background-color: var(--colorbg1) !important;
		border-bottom-width: 0 !important;
	}

	.nav-link{
		border-color: var(--color1)
	}

</style>