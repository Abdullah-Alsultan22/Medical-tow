<template>

    <header>        
        <div  class="container">
            <div class="logo">
                <img alt="logo" src="@/assets/global/logo.jpg" />
              
            </div>
            <nav>
                <div class="heden"> <i class="fas fa-bars toggle-menu"></i></div>
                <ul> 
                    <li><a href="#home">صفحة الهوم</a></li>
                    <li><a href="#medical">Medical</a></li>
                    <li><a href="#about">About us</a></li>
                    <li><a href="#team">Our Team</a></li>
                    <li><a href="#Strategy">Our Strategy</a></li>
                    <li><a href="#ourpartners">Our Partners</a></li>
                    <li><a href="#TimeLine">TimeLine</a></li>
                </ul>
            </nav>
    <img class="seach" src="../assets/global/searsh.svg" alt="">
        </div>
    </header>  
</template>


<script>
 import { Navigation, Pagination, Scrollbar, A11y } from 'swiper';
export default {
    name: "AppHeader",
};
</script>

<style scoped>


/* Small */
@media (min-width: 768px) {
    .container {
        width: 750px;
    }
}

/* Medium */
@media (min-width: 992px) {
    .container {
        width: 970px;
    }
}

/* Large */
@media (min-width: 1200px) {
    .container {
        width: 1170px;
    }
}


header {
    left: 0;
    width: 100%;
    z-index: 2;
    background-color: #cefbf9;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    min-height: 100px;
}

.logo {
    height: 90px;
    margin: 10px;
}

nav {
    flex: 1;
    height: 50px;
    width: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: white;
    border-radius: 50px;
    border: 1px solid #eee;
}

.container .toggle-menu {
    color: white;
    font-size: 22px;
    height: 100%;
}

@media (min-width: 768px) {
    header nav .toggle-menu {
        display: none;
    }
}
nav ul {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    list-style: none;
width: 100%;
}

@media (max-width: 767px) {
    header nav ul {
        display: none;
        background-color: none;
    }

    .container.toggle-menu:hover+ul {
        display: flex;
        flex-direction: column;
        position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        background-color: rgb(0 0 0 / 50%);
    }

    nav ul li a {
        padding: 15px !important;
    }
}

nav > * {
    height:100%;
}



nav ul li a {
    padding: 8px 10px;
    color: black;
    text-decoration: none;
    font-size: 14px;
    transition: 0.1s;
    position: relative;
    z-index: 2;
    height: 100%;
    font-weight: bold;
}

nav ul li a.active,
nav ul li a:hover {
    color: #2F6044;
    border-bottom: 2px solid #2F6044;
}

.seach {
    width: 40px;
    height: 39px;
    background-color: white;
    border-radius: 50px;
    border: 2px solid white;
    cursor: pointer;
    margin: 20px;
}
</style>
