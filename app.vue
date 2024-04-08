<template>
	<h1 class="text-3xl font-bold underline">
		Steve O'Brien
	</h1>
</template>

<script setup lang="ts">
useHead({
	title: 'Steve O\'Brien',
	meta: [
		{ name: 'description', content: 'My amazing site.' }
	],
	htmlAttrs: {
		class: 'h-full'
	},
	bodyAttrs: {
		class: 'font-sans antialiased text-black min-h-full flex flex-col'
	},
	script: [{ innerHTML: 'console.log(\'Hello world\')' }]
})
</script>