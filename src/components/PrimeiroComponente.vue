<template>
    <div>
        <h1>Primeiro Componente</h1>
    </div>
</template>


<!-- scope o style vai ser so no componente, não vai ser herdado -->
<style scoped> 
div{
    background-color: #0e7e28;
    padding: 20px;
    margin: 30px;
    border-radius: 5px;
    text-align: center;
}

div:hover{
    background-color: #13b939;
}

h1{
    color: white;
    margin-bottom: 10px;

}
</style>