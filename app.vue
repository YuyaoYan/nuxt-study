<template>
	<div>
		<!-- <NuxtWelcome /> -->
		<!-- <NuxtPage /> -->
		<NuxtLayout>
			<NuxtPage />
		</NuxtLayout>
	</div>
</template>
<script setup lang="ts">
useHead({
  // 作为字符串，
  // 其中`%s`会被标题替换
  titleTemplate: '网站标题'
})
</script>
<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style>