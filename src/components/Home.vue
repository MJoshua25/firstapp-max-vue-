<template>
	<div>
		<p>Server Status: {{ status }}</p>
		<hr>
		<button @click="changeStatus">Change Status</button>
	</div>
</template>

<script>
export default {
	name: "Home",
	data: function () {
		return {
			status: 'Critical'
		};
	},
	methods: {
		changeStatus() {
			this.status = 'Normal';
		}
	}
}
</script>

<style scoped>

</style>