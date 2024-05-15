<template>
<div class="sobreNos">
    <!--<button class="contato btn btn-danger btn-lg" @click="alternaVisibilidade">Sobre nós</button> -->
    <div v-if="mostrarSM">
        <div class="textoSN">
            <h1 class="tituloSN">Sobre nós</h1>
            <p>Fundada em 24 de Junho de 1980, a Lince, Holding das empresas Circulo e Plasvale, centraliza o desenvolvimento dos sistemas corporativos, aplicativos e soluções de TI das empresas do grupo. Após décadas de atendimento às nossas empresas, estamos crescendo e expandindo nossos horizontes.</p>
            <p>Nossa proposta de valor é potencializar e gerar negócios classe mundial, através das pessoas, tecnologia e inovação. Nosso impulso é o aproveitamento do ecossistema do grupo, 
                a busca de novos negócios e novos mercados, e assim rompermos a fronteira do grupo, impactando muito mais pessoas e negócios.</p> 
        </div>
    </div>
</div>
</template>

<script>
export default {
    components: {},

    data() {
        return {
            mostrarSM: true
        }
    },
    methods: {
        alternaVisibilidade() {
            this.mostrarSM = !this.mostrarSM;
        }
    }
}
</script>

<style>
.sobreNos {
    margin: 2em;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #C51631;
    box-sizing: border-box; /* Inclui bordas e padding no cálculo da largura e altura */
    padding: 0; /* Remove o padding */
    margin: 0; /* Remove a margem */
}

.tituloSN{
    color: white;
}

.sobreNos p{
    color: white;
    font-size: larger;
}

.textoSN {
    margin: 1em;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 900px;
}
</style>
