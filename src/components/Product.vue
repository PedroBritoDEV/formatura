<script setup>

    defineProps({
        description : String,
        scr_img : String,
        product_id : Number,
        product_price : Number,
    })
</script>

<template>
    <section :id="product_id">

        <picture>
            <img :src="scr_img" :alt="description" >
        </picture>
        <p>{{ description }}</p>
        <span class="price">R$ {{product_price}}</span>
        <a href="https://api.whatsapp.com/qr/IQU56RO4XL5XP1?autoload=1&app_absent=0"><button>Eu Quero  <i class="fa-brands fa-whatsapp" style="color: #25d366;"></i></button></a>
    </section>
</template>

<style scoped>
    section {
        width: 160px;
        padding: 10px;
        margin: 10px;
        background-color: #306BAC;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        border-radius: .5em;
        color: white;
    }
    section picture {
        width: 150px;
        height: 150px;
        overflow: hidden;
        border-radius: .5em;
        transition: .2s;
    }
    section picture img {
        width: 100%;
        height: 100%;
        border-radius: .5em;
        object-fit: cover;
        transition: .3s;

    }
    section img:hover{
        transform: scale(1.1);
    }
    section a {
        width: 150px;
    }
    section button {
        width: 100%;
        height: 30px;
        border-radius: .5em;
        background-color: #98B9F2;
        border: 2px solid #98B9F2;
        font-weight: 600;
        transition: .3s;
    }
    section button:hover {
        background-color: transparent;
        color: #fff;
    }
</style>
