<template>
    <div>
        <span class="red">{{ mensagem }}</span>
        <teste />
    </div>
</template>
<script>
import Teste from './Teste';

export default {
    name:'App',
    components: {
        Teste
    },
    data(){
        return {
            mensagem:'Olá seja bem-vindo'
        }
    }
}
</script>

<style scoped>
    span.red {
        color:red;
    }
</style>