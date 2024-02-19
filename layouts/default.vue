<template>
	<div>
		<Header />
		<div style="display: flex; padding: 20px">
			<Nav />
			<slot />
		</div>
		<!-- <Footer /> -->
	</div>
</template>
<script setup lang="ts">
const route = useRoute()

useHead({
	meta: [{ property: 'og:title', content: `应用名称 - ${route.meta.title}` }]
})
</script>
