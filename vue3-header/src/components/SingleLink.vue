<template>
    <li>
        {{linkPromp.tipo}}
    </li>
</template>



<script>
import { createApp } from 'vue';
import NavLink from './NavLink.vue';
export default{
    name:SingleLink,

  components:{
    NavLink,
  },
  promps:linkPromp,
}

</script>

<style lang="scss">

    
</style>

<!-- Usando il progetto creato ieri in classe, vue3-header, aggiungere un componente figlio di AppHeader, che si chiami NavLink, istanziare tanti navlink quanti link sono presenti nella navbar e passare il suo nome come prop da AppHeader a NavLink -->