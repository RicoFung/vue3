<script setup>
import { ref } from 'vue'

defineProps({
  title: String
})	

// define value
const message = 'Hello Vue!!'
// defin func
const tap = () => {
	alert("tap")
}
</script>

<template>
	<h1>{{ title }}</h1>
	<div id="hello-vue" class="demo">
	  {{ message }}
	</div>
	<button type="button" @click="tap">Tap</button>
</template>

<style>
</style>