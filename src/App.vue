<template>
  <html>

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="../CSS/landingPage.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  </head>

  <body>
    <TheHeader>
    </TheHeader>
      <!--<main>
        <div class='slogan'>
          <div class="divTextoSlogan">
            <h1 class="textoSlogan">
              POTENCIALIZAR
            </h1>

            <h1>
              NEGÓCIOS ATRAVÉS DE
            </h1>

            <h1>
              PESSOAS,
              TECNOLOGIA E INOVAÇÃO
            </h1>
            <button class=" btn btn-danger">CONHEÇA NOSSO ERP</button>
          </div>


          <div class="imgSlogan">
            <img src="/assets/logoLince.png">
          </div>
        </div>

        <div class="frase">"As soluções apresentadas pela Lince são robustas, que proporcionam
          eficiência, agilidade e flexibilidade para as rotinas diárias nas mais diversas
          operações da empresa, entregando informações precisas e ágeis para tomada de decisão,
          sendo fundamentais e estratégicas para a gestão dos negócios."
          - Presidente da Plasvale"
        </div>

        <div class="sobreNos">
          <h1 class="tituloSobre">Sobre nós</h1>
        </div>
      </main>

      <footer>

      </footer>-->
  </body>

  </html>

</template>

<script>
import TheHeader from './components/TheHeader.vue'

export default {
  name: 'App',
  components: {
    TheHeader
  }
}
</script>

<style>
#app {


  @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');


  body {
    font-family: "Roboto", sans-serif;
  }


  .navBar {
    padding: 1em;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
   

  }

  .navBar a {
    text-decoration: none;
    color: #C51631;
    font-size: large;
  }

  .navBar a:hover {
    text-decoration: underline;
    color: black;
    transition: color 0.5s;
  }


  .navBar .logoIMG {
    max-width: 30%;
    height: auto;
  }



  .slogan {
    padding: 3em;
    display: flex;

  }


  .slogan .divTextoSlogan h1 {
    color: #C51631;
  }

  .slogan .divTextoSlogan button {
    margin: 1em;
    font-size: larger;
  }


  .slogan .imgSlogan img {
    margin: 2em;
  }


  .frase {
    color: #C51631;
  }

  .sobreNos {
    background-color: #C51631;


  }

  .sobreNos h1 {
    text-align: center;
    color: white;

  }

}
</style>
