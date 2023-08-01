<script>
    export default {
        name: "rifa"
    }
</script>

<template >

    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#98B9F2" fill-opacity="1" d="M0,64L60,74.7C120,85,240,107,360,117.3C480,128,600,128,720,117.3C840,107,960,85,1080,69.3C1200,53,1320,43,1380,37.3L1440,32L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path></svg>
    <section id="rifa">
        <div class="rifa-content">
            <h2>RIFA</h2>
            <div>
                <img class="premios" src="/img/premio.jpg" alt="">
                <p>Participe da nossa rifa para concorrer a incriveis prêmios e ajudar na nossa formatura.</p>
                <p>Compre seu numero clicando <a href="https://api.whatsapp.com/qr/IQU56RO4XL5XP1?autoload=1&app_absent=0">aqui</a></p>
                <span>ou</span>
                <p>leiao Qr Code</p>
                <img class="qr-code" src="/img/qr-code.jpg" alt="qr-code">
            </div>
        </div>
    </section>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#98B9F2" fill-opacity="1" d="M0,64L60,74.7C120,85,240,107,360,117.3C480,128,600,128,720,117.3C840,107,960,85,1080,69.3C1200,53,1320,43,1380,37.3L1440,32L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z"></path></svg>
</template>

<style scoped>
    section {
        background-color: #98B9F2;
        margin-top: -9px;
        padding: 20px;
    }
    .rifa-content {
        max-width: 1450px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
    }
    .rifa-content h2 {
        color: #141B41;
        padding-left: 10px;
        margin-bottom: 15px;
        font-weight: 800;
        font-size: 2.5em;
        border-left: 10px solid #918EF4;
        border-radius: .2em;
    }
    .rifa-content div {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .rifa-content div img {
        width: 350px;
        border-radius: 1em;
        margin: 20px 0;
    }
    .qr-code {
        width: 250px!important;
    }
    .rifa-content div p {
        font-size: 1.2em;
        font-weight: 500;
    }
</style>