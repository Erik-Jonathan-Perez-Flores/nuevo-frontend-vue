<template>
  <div>
  	<component :is="layout"></component>
  </div>
</template>
<script>
	import materias from '@/views/layouts/layoutMaterias.vue'
	import practicas from '@/views/layouts/layoutPracticas.vue'
	import {mapState} from 'vuex'
	export default{
		components:{
			'login-layout':materias,
			'principal-layout':practicas
		},
		computed: mapState(['layout'])
		
	}
</script>
<style>
	
</style>


