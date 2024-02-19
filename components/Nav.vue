<template>
	<div class="nav-container">
		<ul>
			<li><NuxtLink to="/button">button</NuxtLink></li>
			<li><NuxtLink to="/icon">icon</NuxtLink></li>
		</ul>
	</div>
</template>
<script>
export default {
	data() {
		return {}
	},
	methods: {}
}
</script>

<style scoped>
.nav-container {
	height: 400px;
	width: 15%;
	border-right: 1px solid rgba(128, 208, 255, 0.479);
	font-size: 18px;
	line-height: 18px;
}
</style>
