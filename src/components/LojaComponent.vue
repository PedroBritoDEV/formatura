<script setup>
    import Product from "./Product.vue"
</script>

<template>
    <main>
        <div class="main-content">
            <h2>LOJA</h2>
            <div class="produtos">
                <Product description="Cupcake" product_id="1" scr_img="../public/img/cupcake.jpg" product_price="4.00" />
                
                <Product description="Brigadeiro" product_id="2" scr_img="../public/img/brigadeiro.jpg" product_price="1.00" />

                <Product description="Sorvete" product_id="3" scr_img="../public/img/sorvete.jpg" product_price="2.00" />

                <Product description="Mousse" product_id="4" scr_img="../public/img/mouse.jpg" product_price="2.50" />

                <Product description="Cremosinho" product_id="5" scr_img="../public/img/cremosinho.jpg" product_price="2.00" />

                <Product description="Bolo" product_id="6" scr_img="../public/img/bolo.jpeg" product_price="4.50" />

                <Product description="Pipoca Fest" product_id="7" scr_img="../public/img/pipoca-fest.jpg" product_price="1.50" />

                <Product description="Amendupã" product_id="8" scr_img="../public/img/pipoca-amendupa.jpg" product_price="2.00" />

                <Product description="Halls" product_id="9" scr_img="../public/img/halls.jpg" product_price="2.00" />

                <Product description="Pizza Brotinho" product_id="10" scr_img="../public/img/pizzabrotinho.jpg" product_price="2.00" />
                <Product description="Bom Bom" product_id="11" scr_img="../public/img/sonhodevalsa.jpg" product_price="1.00"/>

                <Product description="Pirulito" product_id="12" scr_img="../public/img/pirulito.jpg" product_price="0.50" />

            </div>
            

        </div>
    </main>
</template>

<style scoped>
    .main-content {
        max-width: 1450px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
    }
    .main-content h2 {
        color: #141B41;
        padding-left: 10px;
        margin: 15px;
        font-weight: 800;
        font-size: 2.5em;
        border-left: 10px solid #918EF4;
        border-radius: .2em;
        float: left;

    }
    .main-content .produtos {
        display: flex;
        flex-wrap: wrap;
        margin: 0 auto;
        justify-content: space-between;
    }
</style>
