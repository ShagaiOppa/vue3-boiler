<template>
	<div>About</div>
	<div>{{ userName }}</div>
</template>

<script setup>
import { computed } from 'vue'
import { useStore } from 'vuex'
const store = useStore()

const userName = computed(() => {
	return store.state.user.name
})
</script>

<style></style>
