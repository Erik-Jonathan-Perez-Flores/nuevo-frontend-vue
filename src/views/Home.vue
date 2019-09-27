<template>
  <div>
    <!--<img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <listado/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import listado from '@/components/materias/listadoMaterias.vue'
export default {
  name: 'home',
  components: {
    //HelloWorld
    listado
    
  }
}
</script>
