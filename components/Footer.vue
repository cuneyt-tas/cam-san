<template>

	<footer class="container">

		<p>Tüm Hakları Saklıdır. © {{ currentYear }} CAM-SAN</p>

	</footer>

</template>

<script>

	export default {

		computed: {
			currentYear() {

				var d = new Date();
				return d.getFullYear();

			}
		}

	}

</script>

<style lang="scss">



</style>
