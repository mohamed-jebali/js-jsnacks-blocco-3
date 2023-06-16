<template>
    <header>
        <NavLink/>
    </header>
</template>



<script>
import { createApp } from 'vue'
export default{
    name:'AppHeader',

  components:{
    AppHeader,
    NavLink,
    SingleLink
  }
}

</script>

<style lang="scss">

    
</style>

<!-- Usando il progetto creato ieri in classe, vue3-header, aggiungere un componente figlio di AppHeader, che si chiami NavLink, istanziare tanti navlink quanti link sono presenti nella navbar e passare il suo nome come prop da AppHeader a NavLink -->