<template>
    <div>
        <h1>Componente com dados</h1>
        <p>Nome: {{ nomeProduto }} - {{ codigoProduto }}</p>
    </div>
</template>

<style>
div{
    text-align: center;
    border: 2px solid rgb(10,69,4);
    background-color: #050d04;
    border-radius: 15px;
    margin: 30px;
    padding: 10px;
}
</style>

<!-- <script>
// options API
// export default{
//     data:function(){
//         return{
//             nomeProduto: "Caderno",
//             codigoProduto: "#321"
//         }
//     }
// }

// composition API
// export default{
//     setup:function(){
//         const nomeProduto= "Lápis"
//         const codigoProduto = "#789"
//         return {nomeProduto, codigoProduto}

//     }
// }
</script> -->

<script setup>
        const nomeProduto= "Lápis"
        const codigoProduto = "#789"
</script>