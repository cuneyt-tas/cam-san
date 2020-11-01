<template>

	<header class="container">

		<div class="top-header">

			<figure class="logo">

				<a href="/" title="Cam-San Ana Sayfa">

					<img src="~/assets/image/cam-san-logo.png" alt="Cam-San Logo"/>

				</a>

			</figure>

			<div class="social-media">

				<a href="#" class="facebook" target="_blank" title="Cam-San Facebook Sayfası">

					<i class="fab fa-facebook-f"></i>

				</a>

				<a href="#" class="twitter" target="_blank" title="Cam-San Twitter Sayfası">

					<i class="fab fa-twitter"></i>

				</a>

				<a href="#" target="_blank" title="Cam-San Google Yorumları Sayfası">

					<i class="fab fa-google"></i>

				</a>

			</div>

		</div>

		<Navigation />

	</header>

</template>

<style lang="scss">

	header {
		margin-top: 50px;
		box-shadow: 0 0 5px #aaa;

		.top-header {
			background-color: $white;
			border-top: 7px solid $red;
			padding: 50px;
			display: flex;
			justify-content: space-between;
			align-items: center;

			.social-media {

				a {
					color: $red;
					font-size: 40px;

					&:not(:last-child) {
						margin-right: 40px;
					}

					&:hover {
						color: $black;
					}

					&.facebook {

						&:hover {
							color: #3b5998;
						}

					}

					&.twitter {

						&:hover {
							color: #5ea9dd;
						}

					}

				}

			}

		}

	}

</style>
