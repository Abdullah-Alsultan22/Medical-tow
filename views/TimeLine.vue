<template>
  <div id="TimeLine" class="timeline">
    <div class="container">
      <h2>TimeLine for Campany</h2>
      <p>
        Temmam Pharma represents and aims to be the agent of major and minor
        multinational pharmaceutical industries worldwide
      </p>
      <div class="lines">
        <div class="main-line"></div>
        <div class="details">
          <div class="data-bott">
            <div class="cercal"></div>
            <div class="bor">
              <div class="con-bott">
                <img class="one" src="../assets/global/timlin.svg" alt="">
                <div class="number">1999</div>
                <div class="name">expansion</div>
              </div>
            </div>
          </div>
          <div class="data-top">
            <div class="bor">
              <div class="con-top">
                <img class="tow" src="../assets/global/timlin.svg" alt="">
              <div class="number">2005</div>
              <div class="name">Trust and commitment</div>
            </div></div>
            <div class="cercal"></div>
          </div>
          <div class="data-bott">
            <div class="cercal"></div>
            <div class="bor">
              <div class="con-bott">
                <img class="three" src="../assets/global/timlin.svg" alt="">
              <div class="number">2010</div>
              <div class="name">Competitiveness</div></div>
            </div>
          </div>
          <div class="data-top">
            <div class="bor">
              <div class="con-top">
                <img class="four" src="../assets/global/timlin.svg" alt="">
              <div class="number">2015</div>
              <div class="name">continuity</div>
              </div>
            </div>
            <div class="cercal"></div>
          </div>
          <div class="data-bott-fiv">
            <div class="cercal"></div>
            <div class="bor">
              <div class="con-bott">
                <img class="five" src="../assets/global/timlin.svg" alt="">
              <div class="number-fiv">2022</div>
              <div class="name">Temmam Pharma Establishment</div>
            </div></div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TimeLine",
};
</script>

<style>
.timeline {
  padding: 0 5%;
  margin-bottom: 100px;
}
.timeline h2 {
  color: #2f6044;
  font-weight: bold;
  text-align: center;
  font-size: 30px;
}
.timeline .container {
  font-weight: bold;
  text-align: center;
  margin-top: 5%;
  position: relative;
}
.timeline .container p {
  text-align: start;
  color: #707070;
  font-size: 18px;
  margin-bottom: 8%;
}
.timeline .lines {
  position: relative;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100px;
}
.timeline .main-line {
  width: 66%;
  height: 1px;
  background-color: #2cc2bd;
  position: relative;
  left: -60px;
}
.timeline .details {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.timeline .cercal {
  width: 15px;
  height: 15px;
  background-color: #2cc2bd;
  border-radius: 50%;
  position: relative;
  right: -57px;
}
.timeline .data-bott {
  height: 58.5%;
  margin-top: auto;
  position: relative;
}
.timeline .data-bott-fiv {
  position: relative;
    top: 37px;
}
.timeline .data-bott-fiv .number-fiv {
  position: relative;
  right: -57px;
  text-align: start;
  color: #2cc2bd;
}
.timeline .data-top {
  height: 95%;
  margin-top: auto;
  position: relative;
  top: -50px;
}
.timeline .lines .number {
  color: #2cc2bd;
  font-weight: bold;
  text-align: center;
}
.timeline .lines .name {
  font-weight: bold;
  color: #707070;
  text-align: start;
}

.con-bott {
  border: 1px solid #bbd7d675;
  border-radius: 10px;
  background-color: white;
position: relative;
bottom: -9px;
}
.con-bott  .one {
  position: relative;
    top: -15px;
    left: 23px;
    width: 20px;
}
.con-top  .tow{
  transform: rotate(180deg);
    position: relative;
    bottom: -78px;
    left: -22px;
    width: 30px;
}
.con-bott  .three {
  position: relative;
  width: 20px;
  top: -15px;
  
}
.con-top .four{
  transform: rotate(180deg);
    position: relative;
    bottom: -79px;
    width: 31px;
    left: 24px;
}

.con-bott  .five{
  position: relative;
  width: 20px;
  top: -15px;
}

.con-top{
  border: 1px solid #bbd7d675;
    border-radius: 10px;
    background-color: white;
    position: relative;
    top: -9px;
    height: 83px;
}
</style>
