<template>

	<nav>

		<NuxtLink to="/" title="Cam-San Ana Sayfa">Ana Sayfa</NuxtLink>
		<NuxtLink to="/urunler" title="Cam-San Ürünleri">Ürünler</NuxtLink>
		<NuxtLink to="/hakkinda" title="Cam-San Hakkında">Hakkında</NuxtLink>
		<NuxtLink to="/iletisim" title="Cam-San İletişim Sayfası">İletişim</NuxtLink>

	</nav>

</template>

<style lang="scss">

	nav {
		background-color: $red;
		padding: 10px 20px;

		a {
			font-size: 15px;
			line-height: 25px;
			text-transform: uppercase;
			text-decoration: none;
			color: $white;

			&:hover {
				text-decoration: underline;
				color: $white;
			}

			&:not(:last-child) {
				margin-right: 30px;
			}

		}

	}

</style>
