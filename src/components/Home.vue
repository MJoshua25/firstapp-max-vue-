<template>
	<div class="Home">
		<app-server-status></app-server-status>
	</div>
</template>

<script>
import ServerStatus from "@/components/ServerStatus";

export default {
	name: "Home",
	components: {
		'app-server-status': ServerStatus
	}
}
</script>

<style scoped>

</style>