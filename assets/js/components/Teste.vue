<template>
    <div>
        <h2>Testando 1, 2, 3</h2>
        <input type="text" v-model="nome" />
    </div>
</template>
<script>
export default {
    name:'Teste',
    data(){
        return {
            nome:'Neno'
        }
    }
}
</script>

<style scoped>
    span.red {
        color:red;
    }
</style>