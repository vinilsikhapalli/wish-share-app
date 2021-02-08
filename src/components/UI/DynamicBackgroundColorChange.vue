<template>
    <div>
        <h1 class="text-light">Pure CSS Animated Gradient Background</h1>
<h6 class="text-light small font-weight-bold"><i class="fas fa-code"></i> with <i class="fas fa-heart"></i> by Manuel Pinto</h6>
    </div>
</template>
<style >
body {
	background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
	background-size: 400% 400%;
	animation: gradient 15s ease infinite;
}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
</style>