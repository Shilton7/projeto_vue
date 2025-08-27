<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
export default{
    name: 'LifeCycle',
    data(){
        return{
            nome: 'ainda não sei'
        }
    },
    created(){
        setTimeout(() =>{
        this.nome = 'Luiz Fernando'
        }, 1000);
    },
    mounted(){
        setTimeout(() =>{
        this.nome = 'Fulano'
        }, 2000);
    }
}

</script>
