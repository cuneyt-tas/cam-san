<template>

	<div class="call-to-action">

		<h1>{{ actionTitle }}</h1>
		<NuxtLink to="/iletisim" class="button" title="Cam-San İletişim Sayfası">{{ buttonLabel }}</NuxtLink>

	</div>

</template>

<style lang="scss">



</style>

<script>

	export default {

		props: {

			actionTitle: {
				type: String,
				default: "Cam-San Ticaret Web Sitesine Hoşgeldiniz."
			},
			buttonLabel: {
				type: String,
				default: "Bize Buradan Ulaşabilirsiniz"
			},
			buttonLink: {
				type: String,
				default: "/iletisim"
			},
			buttonTitle: {
				type: String,
				default: "Cam-San İletişim Sayfası"
			},

		}

	}

</script>
