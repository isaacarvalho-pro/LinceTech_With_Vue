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

    <MainContent>
    </MainContent>

    <SobreNos>
    </SobreNos>

    <BoasManeiras>
    </BoasManeiras>

  </body>

  </html>

</template>

<script>
import TheHeader from './components/TheHeader.vue'
import MainContent from './components/MainContent.vue' 
import SobreNos from './components/SobreNos.vue';
import BoasManeiras from './components/BoasManeiras.vue'

export default {
  name: 'App',
  components: {
    TheHeader,
    MainContent,
    SobreNos,
    BoasManeiras,
  },
}
</script>

<style>
#app {


  @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');


  body {
    font-family: "Roboto", sans-serif;
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


}
</style>
