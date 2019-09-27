<template>
	<div>
		<div class="content">
			<div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
				<div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 spaciofinal" >
					<li>
						<router-link :to="'/practicas/'+1">Materia 1</router-link>
					</li>
				</div>
				<div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 spaciofinal" >
					<li>
						<router-link :to="'/practicas/'+2">Materia 2</router-link>
					</li>
				</div>
				<div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 spaciofinal" >
					<li>
						<router-link :to="'/practicas/'+3">Materia 3</router-link>	
					</li>
				</div>
				<div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 spaciofinal" >
					<li>
						<router-link :to="'/practicas/'+4">Materia 4</router-link>
					</li>
				</div>
				<div class="col-lg-4 col-md-4 col-sm-6 col-xs-12 spaciofinal" >
					<li>
						<router-link :to="'/practicas/'+5">Materia 5</router-link>	
					</li>
				</div>
			</div>
		</div>
	</div>
</template>
<script>
	export default{
		name:'listado',
		 created () {
            this.$store.commit('SET_LAYOUT', 'login-layout')
        }
		
	}
</script>
<style scope>
	.spaciofinal{
		margin-bottom:30px;
	}
</style>