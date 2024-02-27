<script>
export default {
	data() {
		return {};
	},
	methods: {},
};
</script>

<template>
	<section>
		<nav class="navbar bg-primary">
			<div class="container d-flex justify-content-between">
				<div>
					<font-awesome-icon icon="fa-brands fa-discord" size="2x" />
					<a class="navbar-brand" href="#">Discord</a>
				</div>
				<div>
					<a class="navbar-brand" href="#">Scarica</a>
					<a class="navbar-brand" href="#">Nitro</a>
					<a class="navbar-brand" href="#">Scopri</a>
					<a class="navbar-brand" href="#">Sicurezza </a>
					<a class="navbar-brand" href="#">Assistenza</a>
					<a class="navbar-brand" href="#">Blog</a>
					<a class="navbar-brand" href="#">Lavora con noi</a>
				</div>
				<div>
					<button class="btn btn-light rounded-pill">Apri discord</button>
				</div>
			</div>
		</nav>
	</section>
	<!-- SEZIONE DELL/ HEADER CON JUMBOTRON INIZIALE -->
	<div class="card-box">
		<div class="container text-center mt-5">
			<h1 class="text">Il tuo posto per parlare</h1>
			<p class="text">
				Che tu faccia parte di un club scolastico,gruppo di gamer,comunità artistica <br />
				mondiale,o semplicemente di un piccolo gruppo di amici che vuole passare il tempo <br />
				assieme,Discord rende più facile chiacchierare ogni giorno e ritrovarsi più spesso.
			</p>
			<div class="button d-flex justify-content-center">
				<button class="btn btn-light rounded-pill"><font-awesome-icon :icon="['fas', 'arrow-down']" /> Scarica per Mac</button>
				<button class="btn btn-light rounded-pill">Apri Discord nel tuo browser</button>
			</div>
		</div>
	</div>
	<section></section>
</template>

<style scoped>
nav {
	color: white;
	a {
		color: white;
	}
}
.card-box {
	background-image: url(../../public/img/jumbo.png);
	min-height: 400px;
	padding: 2rem 0;
	background-size: cover;
}
</style>
.
