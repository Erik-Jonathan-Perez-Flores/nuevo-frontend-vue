<template>
	<div>
	 	<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
	 		<h1>Aquí van las practicas de la materia : {{$route.params.id}}</h1>
	 	</div>
	</div>
</template>
<script>
	  export default {
        created () {
            this.$store.commit('SET_LAYOUT', 'principal-layout')
        }
    }
</script>
<style>
	
</style>