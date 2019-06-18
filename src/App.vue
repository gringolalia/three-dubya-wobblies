<template lang="pug">
#app
	.w3-bar.w3-blue-grey.w3-large.w3-padding-24
		a.w3-bar-item.w3-button.w3-hover-black(style="font-size: 21px;")
			i.fas.fa-chess.fa-2x.w3-margin-right
			| Engenho Novo Versão Xadrez
		a.w3-bar-item.w3-button.w3-hover-black.w3-right.w3-margin-right San Pavlov
		a.w3-bar-item.w3-button.w3-hover-black.w3-right.w3-margin-right Ubatuba
		a.w3-bar-item.w3-button.w3-hover-black.w3-dropdown-hover.w3-right.w3-margin-right
			| Sambodia &nbsp;
			i.material-icons expand_more
			.w3-dropdown-content.w3-bar-block.w3-card-4
				a.w3-bar-item.w3-button(href='#')
					i.fas.fa-sun.fa-lg.w3-margin-right
					| Samba
				a.w3-bar-item.w3-button(href='#')
					i.fas.fa-star-and-crescent.fa-lg.w3-margin-right
					| Choro
				a.w3-bar-item.w3-button(href='#')
					i.fas.fa-mercury.fa-lg.w3-margin-right
					| Marchinhas
				a.w3-bar-item.w3-button(href='#')
					i.fas.fa-fighter-jet.fa-lg.w3-margin-right
					| Pagode
				a.w3-bar-item.w3-button(href='#')
					i.fas.fa-space-shuttle.fa-lg.w3-margin-right
					| Baião
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-moon.fa-lg.w3-margin-right
					| Frevo
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-mercury.fa-lg.w3-margin-right
					| Forró
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-mosque.fa-lg.w3-margin-right
					| Xote
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-broadcast-tower.fa-lg.w3-margin-right
					| Maracatú
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-chess-knight.fa-lg.w3-margin-right
					|Coco de Repente
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-tv.fa-lg.w3-margin-right
					| Hip-Hop
				a.w3-bar-item.w3-button(href='#')
					i.fa.fa-users.fa-lg.w3-margin-right
					| Bossa Nova
	router-view
</template>

<script>
export default {
	name: 'App'
}
</script>

<style>
#app {
	font-family: 'News Cycle', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
</style>
