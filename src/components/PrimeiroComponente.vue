<template>
    <div>
    <h1>Olá vue</h1>
    <p>Meu Nome é: {{ nome }} e trabalho como {{ profissao }}</p>
    </div>
</template>

<script>
export default{
    name: 'PrimeiroComponente',
    data(){
        return{
            nome: "Luiz Fernando",
            profissao: "Desenvolvedor"
        }
    }
}
</script>
