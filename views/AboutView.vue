<template>
     <div class="line"></div>
    <div class="about" id="about">
   
        <div class="container">
            <h3>About US</h3>
            <p>Temmam Pharma represents and aims to be the agent of major and minor
multinational pharmaceutical industries worldwide and partner with
international NGOs in the country to pave the way for better access for.<br>
Temmam Pharma represents and aims to be the agent of major and minor
multinational pharmaceutical industries worldwide and partner with
international NGOs in the country to pave the way for better access for.<br>
Temmam Pharma represents and aims to be the agent of major and minor
multinational pharmaceutical industries worldwide and partner with
international NGOs in the country to pave the way for better access for.
            </p>
            <img src="../assets/global/dr1.1.png" alt="">
        </div>
    </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'AboutView',
  components: {
    HelloWorld
  }
}
</script>

<style>
.about {
    position: relative;
    padding: 0 5%;
    margin-top: 50px;
}

.about .container h3 {
    font-weight: bold;
    text-align: start;
    color:#2F6044;
    font-size: 30px;
}

.about .container p {
  position: relative;
    right: 0%;
    height: 300px;
    text-align: start;
    color: #707070;
    font-size: 18px;
    width: 50%;
    font-weight: bold;
  }
  .about .container img {
    position: absolute;
    bottom: 0px;
    width: 50%;
    height: 115%;
    right: 10px;
    object-fit: contain;
}
.line {
  border-bottom: 0.5px solid rgb(204, 204, 204);
  width: 100%;

}
</style>