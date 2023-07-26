<script setup>
    import Product from "./Product.vue"
</script>

<template>
    <main>
        <div class="main-content">
            <h2>LOJA</h2>
            <div class="produtos">
                <Product description="Cupcake" product_id="1" scr_img="https://images.pexels.com/photos/1055272/pexels-photo-1055272.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" product_price="4.00" />
                
                <Product description="Brigadeiro" product_id="2" scr_img="https://images.pexels.com/photos/9285189/pexels-photo-9285189.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" product_price="1.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="4" scr_img="https://amoradoceria.com.br/wp-content/uploads/2021/10/mousse-para-vender.jpg" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

                <Product description="Sorvete" product_id="3" scr_img="https://images.pexels.com/photos/1362534/pexels-photo-1362534.jpeg?auto=compress&cs=tinysrgb&w=600" product_price="2.00" />

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
    }
    .main-content .produtos {
        display: flex;
        flex-wrap: wrap;
        margin: 0 auto;

    }
</style>
