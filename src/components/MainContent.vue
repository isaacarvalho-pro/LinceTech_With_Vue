<template>
    <div class="slogan">
        <p class="textoSlogan">POTENCIALIZAR</p>
        <p class="textoSlogan">NEGÓCIOS ATRAVÉS DE</p>
        <p class="textoSlogan">PESSOAS, TECNOLOGIA E INOVAÇÃO.</p>
    </div>

    


    <div class="saibaMais">
        <button class="contato btn btn-danger btn-lg" @click="alternaVisibilidade">Saiba Mais</button>
        <div v-if="mostrarSM">
            <div class="textoSM">
                <h1 class="titulo">Saiba Mais sobre Nossa Solução de ERP</h1>
                <p>Descubra como nossa solução de ERP pode transformar a maneira como você faz negócios. </p>
                <p>Com uma combinação de tecnologia de ponta e expertise em gestão empresarial, estamos aqui para
                    impulsionar o crescimento e a eficiência de sua empresa.</p>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    components: {
    },

    data() {
        return {
            mostrarSM: false
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
.slogan {
    margin-left: 1em;
    display: flex;
    font-size: 2em;
    color: #C51631;
    flex-direction: column;
}

.textoSlogan {
    font-weight: 900;

}

.saibaMais {
    margin: 2em;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

}

.textoSM {
    margin: 1em;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.titulo {
    color: #C51631;
    font-size: xx-large;
}
</style>