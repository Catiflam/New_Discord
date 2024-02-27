<script>
export default {
	data() {
		return {};
	},
};
</script>
<template>
	<section>
		<div class="container-sm text-center">
			<div class="row justify-content-evenly align-items-center p-3">
				<div class="col-6"><img src="../../public/img/item1.svg" alt="image-1" /></div>
				<div class="col-3 mt-5">
					<h2>Un luogo a invito con tutto lo spazio necessario per parlare</h2>
					<p>I server Discord sono organizzati in canali telematici in cui puoi collaborare. condividere o semplicemente parlare della tua giornata senza intasare una chat di gruppo.</p>
				</div>
			</div>
		</div>
	</section>
	<section class="gray-box">
		<div class="container-sm text-center">
			<div class="row justify-content-evenly align-items-center p-3">
				<div class="col-3 mt-5">
					<h2>Dove trovarsi è facile</h2>
					<p>Mettiti comodo in un canale vocale quando hai tempo. gli amici nel tuo server possono vedere che sei li e unirsi istantaneamente senza dover chiamare.</p>
				</div>
				<div class="col-6">
					<img src="../../public/img/item2.svg" alt="image-2" />
				</div>
			</div>
		</div>
	</section>
	<section>
		<div class="container-sm text-center">
			<div class="row justify-content-evenly align-items-center p-3">
				<div class="col-6"><img src="../../public/img/item3.svg" alt="image-3" /></div>
				<div class="col-3 mt-5">
					<h2>Da pochi a un fandom</h2>
					<p>Dai inizio a una community di qualsiasi dimensione con strumenti di moderazione e accesso ai membri personalizzabile. Concedi ai membri poteri speciali,crea canali privati,e molto altro.</p>
				</div>
			</div>
		</div>
	</section>
	<section class="gray-box">
		<div class="container-sm text-center">
			<div class="row justify-content-evenly align-items-center p-3">
				<div class="mt-5 w-50">
					<h2>Tecnologia affidabile per tenersi in contatto</h2>
					<p>Video e audio a bassa latenza ti faranno sentire come se foste tutti nella stessa stanza.Fai ciao in video, guarda gli amici giocare in streaming, o riunitevi in una sessione di disegno con la condivisione schermo.</p>
				</div>
				<div class="">
					<img src="../../public/img/item4-big.svg" alt="image-4" />
					<h2>Pronto a iniziare la tua avventura?</h2>
					<button class="btn btn-light rounded-pill">
						<font-awesome-icon :icon="['fas', 'arrow-down']" />
						scarica per Mac
					</button>
				</div>
			</div>
		</div>
	</section>
</template>
<style scoped>
.gray-box {
	background-color: rgb(179, 179, 179);
}
</style>
