<template>
	<div class="navbar">
		<a class="navbar-itemL" href="https://google.com/">Home</a>
		<a class="navbar-itemL" href="https://google.com/">Store</a>

		<div>
			<img src="/logo.png" class="logo" alt="Wicked Fits" oncontextmenu="return false;" draggable="false"/>
		</div>

		<a class="navbar-itemR" href="https://google.com/">Promotions</a>
		<a class="navbar-itemR" href="https://google.com/">Stickers</a>
	</div>
	
</template>

<style scoped>
@font-face {
    font-family: SkaterPack;
    src: url("./Skater Pack.ttf");
}

.logo {
	height: 12em;
	will-change: filter;
	transition: filter 300ms;
	animation-name: logo-init;
	animation-duration: 5s;
	animation-iteration-count: 1;
}

.navbar {
	display: flex;
	justify-content: space-around;
	height: 12em;
	width: 100%;
	/* animation-name: navbar-init;
	animation-duration: 5s;
	animation-iteration-count: 1; */
}

.navbar-itemL {
	padding-top: 4em;
	padding-left: 4em;
    font-family: SkaterPack;
    color: #000000;
    text-decoration: underline;
}

.navbar-itemR {
	padding-top: 4em;
	padding-right: 4em;
    font-family: SkaterPack;
    color: #000000;
    text-decoration: underline;
}

@keyframes logo-init {
	0% {
		opacity: 0;
	}
	25% {
		opacity: 0;
	}
	75% {
		opacity: 1;
	}
}

@keyframes navbar-init {
	0% {
		margin-top: 50%;
		opacity: 0;
	}
	25% {
		margin-top: 50%;
		opacity: 0;
	}
	100% {
		margin-top: 0%;
		opacity: 1;
	}
}
</style>
