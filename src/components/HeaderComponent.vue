<script>
    export default {
        name: "header",
        data() {
            return {
                screenWidth: 0,

            };
        },
        methods: {
            toggleDropdown() {
                var dropdownItem = document.getElementById("drop-item")
                dropdownItem.classList.toggle("hidden")
            },
            isMobile() {
                var dropdownItem = document.getElementById("drop-item")
                if(window.innerWidth > 700) {
                    dropdownItem.classList.remove("hidden")
                }else {
                    dropdownItem.classList.add("hidden")
                }
            }
        },
        mounted() {
            this.isMobile()
        }

    }
</script>

<template>
    <header>
        <div class="header-content">
            <div class="logo">
                <img src="/public/img/logo-escola.png" alt="logo">
                <h2>Loja Virtual Teceirão FAB 2023</h2>
            </div>
            <i id="tropdown-btn"  @click="toggleDropdown" class="fa-solid fa-bars"></i>
            <nav>
                <ul id="drop-item" class="hidden">
                    <li><a href="#" target="_blank" rel="">LOJA</a></li>
                    <li><a href="#" target="_blank" rel="">RIFA</a></li>
                    <li><a href="#">VAQUINHA</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped>
    header {
        background-color: #306BAC;
        color: white;
        height: 80px;
        padding: 0 20px;
    }
    .header-content {
        max-width: 1450px;
        margin: 0 auto;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .header-content .logo {
        height: 100%;
        display: flex;
        flex-wrap: wrap;
        align-items: center;

    }
    .header-content .logo img  {
        display: flex;
        width: 60px;
        height: 60px;
    }

    .header-content .logo h2 {
        margin-left: 10px;
        height: 30px;
        
    }
    .header-content #tropdown-btn {
        display: none;
        z-index: 4;
        transition: .3s;
    }
    .header-content nav ul {
        display: flex;
        list-style: none;
        transition: .3s;

    }
    .header-content nav ul li a{
        margin-left: 15px;
        text-decoration: none;
        color: #fff;
        font-weight: 700;
    }
    @media (max-width:700px) {
        header {
            height: 60px;
        }
        .header-content .logo h2 {
            font-size: 1.1em;
        }
        .header-content .logo img  {
            width: 40px;
            height: 40px;
        }
        .header-content nav ul li a {
            border-bottom: 2px solid rgba(130, 54, 128, 0.633);
            padding-right: 10px;

        }
        .header-content #tropdown-btn {
            display: inline-block;
            font-size: 2em;
            position: absolute;
            right: 40px;
        }
        .header-content #drop-item {
            display: flex;
            flex-direction: column;
            background-color:#918ef4;
            border-radius: .4em 0 0 .4em;
            padding: 60px 20px 20px 0;
            position: absolute;
            top: 0px;
            right: 0;
        }
    }
</style>
