<template>
    <ul>
        <SingleLink v-for="item in frutta"
        :linkPromp = 'item'
        />
    </ul>
</template>



<script>
import { createApp } from 'vue'
import AppHeader from './AppHeaderLink.vue';
export default{
    name:NavLink,

  components:{
    SingleLink,
  },
  data(){
    return{
        frutta:[
            {
                colore: "rosso",
                tipo: "Mela",
                peso: "3kg",
            },
            {
                colore: "giallo",
                tipo: "Pera",
                peso: "1kg",
            },
            {
                colore: "arancione",
                tipo: "arancia",
                peso: "2kg",
            }
        ]
    }
  }
}

</script>

<style lang="scss">

    
</style>

<!-- Usando il progetto creato ieri in classe, vue3-header, aggiungere un componente figlio di AppHeader, che si chiami NavLink, istanziare tanti navlink quanti link sono presenti nella navbar e passare il suo nome come prop da AppHeader a NavLink -->