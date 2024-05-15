<template>
<div class="bloco1">
    <div class="slogan">
        <div class="texto">
            <p class="textoSlogan">POTENCIALIZAR</p>
            <p class="textoSlogan">NEGÓCIOS ATRAVÉS DE</p>
            <p class="textoSlogan">PESSOAS, TECNOLOGIA E INOVAÇÃO.</p>
        </div>
        <div class="imgLince">
            <img class="" src="../assets/logoLince.png">
        </div>
    </div>
</div>

<div class="fraseLince">
    <p>“As soluções apresentadas pela Lince são robustas, que proporcionam eficiência, agilidade e flexibilidade para as
        rotinas diárias nas mais diversas operações da empresa, entregando informações precisas e ágeis para 
        tomada de decisão, sendo fundamentais e estratégicas para a gestão dos negócios."</p>
        <p>- Presidente da Plasvale
    </p>
</div>


</template>

<script>

</script>

<style>
.bloco1 {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}

.slogan {
    margin-left: 1em;
    display: flex;
    font-size: 2em;
    color: #C51631;
    flex-direction: row;
}

.texto {
    display: flex;
    flex-direction: column;
    margin-right: 2em;
}

.textoSlogan {
    font-weight: 900;

}



.titulo {
    color: #C51631;
    font-size: xx-large;
}

.imgLince {
    display: flex;
    flex-direction: row;
}

.fraseLince p{
    display: flex;
    text-align: center;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: #C51631;
    width: 800px;
    margin: 0 auto;
    padding: 20px
}
</style>
