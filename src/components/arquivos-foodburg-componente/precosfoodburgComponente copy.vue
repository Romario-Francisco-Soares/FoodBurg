<template>
  <div class="tabelaCombos" v-for="(data, index) in dataItem" v-bind:key="index"></div>
</template>
<script>
export default {
    data(){
        return{
            dataItem:[
                {
                    nome: Barbecue,
                    recheio:{
                        1:"2 bifes",
                        2:"Cheddar",
                        3:"Filé Mignon",
                        4:"Molho Agridoce",
                        5:"Cebola",
                        6:"Milho",
                        7:"Tomate",
                        8:"alface"
                    },
                    preco: 37,50
                }
            ]
        }
    }
}
</script>

<style>
</style>