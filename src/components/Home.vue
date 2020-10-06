<template>
	<p>Server Status: {{ status }}</p>
</template>

<script>
export default {
  name: "Home",
  data: function (){
  	return {
  		status: 'Critical'
	  };
  },
	methods: {

	}
}
</script>

<style scoped>

</style>