<template>
	<div>
		<nuxt-content :document="page" />
    <ContentDoc />
	</div>
</template>

<script>
export default {
	async asyncData({ $content }) {
		const page = await $content('button').fetch()

		return {
			page
		}
	}
}
</script>
