<template>

     <footer>
 <div class="container">
  
            <nav>
                
                <div class="box">
                    <a href="#" class="go-up">
                     <img src="../assets/global/goup.svg" alt="">
                    </a>
                    <a href="" class="logo">
                        <img class="log-one" src="../assets/global/logo.jpg" alt="logo">
                        <img class="log-tow" src="../assets/global/logo2.png" alt="logo">
                     
                    </a>
                    
                </div>
            
                <ul>
                  
                    <li><a class="active" href="#"><img src="../assets/global/fot.svg" alt="">Home</a></li>
                    <li><a href="#"><img src="../assets/global/fot.svg" alt="">Medical</a></li>
                    <li><a href="#"><img src="../assets/global/fot.svg" alt="">About US</a></li>
                  
                </ul>
                <ul>
                    <li><a href="#"><img src="../assets/global/fot.svg" alt="">Our Team</a></li>
                    <li><a href="#"><img src="../assets/global/fot.svg" alt="">Our Strategy</a></li>
                    <li><a href="#"><img src="../assets/global/fot.svg" alt="">Our Partners </a></li>
             
                </ul>
                
                <ul><li><a href="#"><img src="../assets/global/fot.svg" alt="">TimeLine </a></li>
                    <h3>QUICK LINK</h3></ul>
                <div class="social">
                    <h2>Contact US</h2>
                    <p><img src="../assets/global/Icon material-my-location.svg" alt="">  Sana'a - Hail Street</p>
                    <p><img src="../assets/global/cont.svg" alt=""> +967 777-000-000</p>
                    <p><img src="../assets/global/fecbok.svg" alt=""> Temmam Light</p>
                    <i class="fa-solid fa-tricycle"></i>
                </div>
            </nav>
        </div>
    </footer>
</template>

<script>
export default {
name:"AppFooter",
}
</script>

<style>

footer {
    width: 100%;
    padding-top: 5%;
    background-color:#cefbf9;
}


@media (max-width: 1099px) {
    footer .container .link {
        margin-right: 7px;
    }
}

footer .container nav {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
  
}


footer .container nav .box {
    margin-top: 38px;
}

@media (max-width: 767px) {
    footer .container nav .box {
        text-align: center;

    }
}



.box .go-up img{
    width: 30px;
    height: 30px;
    position: relative;
    top: -133px;
    right: -37px;
    background-color: white;
    border-radius: 50%;
}
@media (max-width: 767px) {
    footer .container nav .box .go-up img {
        text-align: center;
        top: 4px;
        left: 30px;

    }
}
footer .container nav ul{
    list-style: none;
    padding-left: 0;
    margin-top: 50px;
}
footer .container nav ul li:hover {
  padding-left: 10px;
  transition: 0.4s;

}
footer .container nav ul li a {
    padding: 10px 10px;
    display: block;
    color: #5B5858;
    text-decoration: none;
    font-size: 17px;
    transition: 0.3s;
    z-index: 2;
    font-weight: bolder;
    width: 47%;
}
nav ul li a img{
    width: 16px;
    height: 15px;
}
footer .social  h2{
    color: #2F6044;
    font-size: 25px;
}
footer ul  h3{
    position: relative;
    top: -94px;
    left: -200%;
    color: #2F6044;
    font-size: 25px;
    margin-top: 25px;
}
footer .container  .social p {
  
    color: #5B5858;
    display: block;
    text-decoration: none;
    font-weight: bolder;
    font-size: 18px;
}
.social p img{
    background-color: white;
    border-radius: 50%;
    border: 2px solid white;
    width: 22px;
    margin-bottom: -6px;
}
footer .log-one{
    width: 185px;
    margin-left: 8px;
}
footer .log-tow{
    width: 100px;
    height: 44px;
    margin-left: 72px;
    margin-top: -15px;
}

@media (max-width: 767px) {
    footer .container nav ul li a {
        flex-direction: column;
        text-align: center;
        font-size: 116;
    }
}

@media (max-width: 767px) {
    .footer .box .line i {
        margin-right: 0;
        margin-bottom: 15px;
    }
}

@media (max-width: 667px) {
    footer .container nav .social {
        margin-left: 100px;
    }
}

@media (max-width: 767px) {
    footer .container nav .social {
        margin-right: 150px;
    }
}



@media (max-width: 767px) {
    footer .container nav svg {
        width: 23px;
        height: 23px;

    }
}

</style>