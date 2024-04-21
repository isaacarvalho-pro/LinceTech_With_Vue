<template>
    <div class="container">
        <header>
            <div class="navBar">
                <a class="logoLink">
                    <img class="logoIMG" src="../assets/logoLince.png">
                </a>
                <a class="navHistoria" href="#historia">Nossa história</a>
                <a class="navSolucao" href="#erp">Soluções</a>
                <a class="navAcademy" href="#academy">Academy</a>
                <button class="contato btn btn-danger" href="#">Entrar em contato</button>
            </div>
        </header>
    </div>
</template>


<script>

</script>


<style>
.navBar {
    padding: 1em;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    /* border-bottom: 1px solid #C51631; */


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
</style>