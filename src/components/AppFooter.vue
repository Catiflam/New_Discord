<script>
export default {
	data() {
		return {};
	},
};
</script>

<template>
	<section class="black-box">
		<div class="container-sm">
			<div class="row">
				<div class="col-2 mt-5"><h2>Il tuo posto per parlare</h2></div>
				<div class="col-2 mt-5">
					<ul>
						<li>prodotto</li>
						<li>scarica</li>
						<li>perchè discord</li>
						<li>nitro</li>
						<li>sicurezza</li>
						<li>assistenza</li>
					</ul>
				</div>
				<div class="col-2 mt-5">
					<ul>
						<li>compagnia</li>
						<li>chi siamo</li>
						<li>lavora con noi</li>
						<li>marchio</li>
						<li>redazione</li>
						<li>negozio</li>
					</ul>
				</div>
				<div class="col-2 mt-5">
					<ul>
						<li>risorse</li>
						<li>scarica</li>
						<li>perchè discord</li>
						<li>nitro</li>
						<li>sicurezza</li>
						<li>assistenza</li>
					</ul>
				</div>
				<div class="col-2 mt-5">
					<ul>
						<li>nome</li>
						<li>perchè discord</li>
						<li>nitro</li>
						<li>sicurezza</li>
						<li>assistenza</li>
					</ul>
				</div>
			</div>
		</div>
	</section>
	<div class="black-box">
		<nav class="navbar">
			<div class="container d-flex justify-content-between">
				<div>
					<font-awesome-icon icon="fa-brands fa-discord" size="2x" />
					<a class="navbar-brand" href="#">Discord</a>
				</div>
				<div>
					<button class="btn btn-light rounded-pill">Apri discord</button>
				</div>
			</div>
		</nav>
	</div>
</template>

<style scoped>
.black-box {
	background-color: rgb(34, 34, 35);
	color: aliceblue;

	a {
		color: aliceblue;
	}

	.container-sm {
		height: 200px;
	}

	ul {
		list-style: none;
	}
}
</style>
