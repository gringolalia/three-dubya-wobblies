<template lang="pug">
.hello
	img(src='../assets/hammer-sickle.svg' width="175px", style="margin-top: 10vh")
	h1 Adeus, Mundo Imundo
	h2 Wisdom of Worldly Wobblies
	h3 Cloned in Sambodia 2018

	button.w3-button.w3-red.w3-large.w3-margin-top.w3-hover-blue-grey.w3-ripple
		i.material-icons all_inclusive
		| &nbsp; Impress Me

	button.w3-button.w3-blue-grey.w3-large.w3-margin-top.w3-hover-black.w3-margin-left(onclick="document.getElementById('id01').style.display='block'")
		i.material-icons beach_access
		| &nbsp; Life, A Beach

	#id01.w3-modal
		.w3-modal-content.w3-card-4.w3-left-align(style="max-width: 500px")
			header.w3-container.w3-blue-grey
				span.w3-button.w3-display-topright.w3-hover-dark-grey.w3-xlarge(onclick="document.getElementById('id01').style.display='none'") &times;

				h2 Modal Holy Moly Rounding

			.w3-container
				p Λορεμ ιπσθμ δολορ σιτ αμετ, περ ερθδιτι σιγνιφερθμqθε ει, εθμ σολθτα ιντερεσσετ αccομμοδαρε cθ. Qθι σονετ επιcθρει ιδ. Εθ μει σαλε qθοδσι. Qθισ βρθτε μελιθσ προ?

			footer.w3-container.w3-blue-grey
				p Fonte: Falha de S. Paulo

</template>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
	font-weight: normal;
}
ul {
	list-style-type: none;
	padding: 0;
}
li {
	display: inline-block;
	margin: 0 10px;
}
a {
	color: #42b983;
}
</style>
