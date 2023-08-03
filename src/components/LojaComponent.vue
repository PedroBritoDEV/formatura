<script setup>
    import Product from "./Product.vue"
</script>

<template>
    <section id="loja">
        <div class="product-content">
            <h2>LOJA</h2>
            <div class="produtos">
                <Product description="Cupcake" product_id="1" scr_img="./img/cupcake.jpg" product_price="4.00"/>
                
                <Product description="Brigadeiro" product_id="2" scr_img="./img/brigadeiro.jpg" product_price="1.00"/>


                <Product description="Mousse" product_id="4" scr_img="./img/mouse.jpg" product_price="2.50"/>

                <Product description="Cremosinho" product_id="5" scr_img="./img/cremosinho.jpg" product_price="2.00"/>

                <Product description="Bolo" product_id="6" scr_img="./img/bolo.jpeg" product_price="4.50"/>

                <Product description="Pizza Brotinho" product_id="10" scr_img="./img/pizzabrotinho.jpg" product_price="2.00"/>
                
                <Product description="Pipoca Fest" product_id="7" scr_img="./img/pipoca-fest.jpg" product_price="2.00"/>

                <Product description="Amendupã" product_id="8" scr_img="./img/pipoca-amendupa.jpg" product_price="2.00"/>

                <Product description="Halls" product_id="9" scr_img="./img/halls.jpg" product_price="2.00"/>


                <Product description="Bom Bom" product_id="11" scr_img="./img/sonhodevalsa.jpg" product_price="1.00"/>

                <Product description="Pirulito" product_id="12" scr_img="./img/pirulito.jpg" product_price="0.50"/>
                
                <Product description="Pirulito Energético" product_id="3" scr_img="./img/pirulito-energetico.jpg" product_price="0.75"/>
            </div>
            

        </div>
    </section>
</template>

<style scoped>
    .product-content {
        max-width: 1450px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
    }
    .product-content h2 {
        color: #141B41;
        padding-left: 10px;
        margin: 15px;
        font-weight: 800;
        font-size: 2.5em;
        border-left: 10px solid #918EF4;
        border-radius: .2em;
        float: left;

    }
    .product-content .produtos {
        display: flex;
        flex-wrap: wrap;
        margin: 0 auto;
        justify-content: space-between;
    }
</style>
