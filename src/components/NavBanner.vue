<template>
	<div class="container-fluid colorbg2">
		<div class="color2 name py-3"> Alexander Naylor </div>
		<nav class="nav nav-tabs nav-fill">
			<router-link to="/" class="nav-link">About</router-link>
			<router-link to="/about" class="nav-link">Projects</router-link>
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
		color: var(--color2) !important;
	}

	.nav-link{
		border-color: var(--color1);
		color: var(--color3);
	}

</style>