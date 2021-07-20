<template>
	<div class="relative min-h-screen flex">
		<SideBar />
		<router-view />
	</div>
</template>

<script setup>
import SideBar from './components/SideBar.vue'
</script>
