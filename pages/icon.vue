<template>
	<div>
    <ContentDoc />
	</div>
</template>

<script>
export default {
	async asyncData({ $content }) {
		const page = await $content('icon').fetch()

		return {
			page
		}
	}
}
</script>
