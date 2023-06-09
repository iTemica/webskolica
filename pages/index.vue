<template>
	<div>
		Count is: {{ count }}
		<button @click="count++">increment</button>

		<button @click="count--">decrement</button>
	</div>
</template>

<script lang="ts" setup>
const count = ref(0);
</script>
