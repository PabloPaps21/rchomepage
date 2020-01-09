<template>
  <div class="our-services">
    <div class="services-container">
      <div class="services-head">
        <h1>Nuestros Servicios</h1>
        <div class="linea"></div>
        <p>
          Somos la compañía de RegTech que
          maximiza el adecuado cumplimiento
          con la información regulatoria solicitada
          por la Comisión Nacional Bancaria y de Valores(CNBV).</p>
      </div>
      <div class="services-colums">
          <div class="col">
            <img src="../../public/70-E-Banking.png" alt="E-Banking">
            <p>Mitiga el riesgo de interpretación</p>
          </div>
          <div class="col">
            <img src="../../public/79-Financial-Report.png" alt="Financial-Report">
            <p>Simplifica la detección de errores</p>
          </div>
          <div class="col">
            <img src="../../public/67-Targets.png" alt="Targets">
            <p> Eficiente y ágil de actualizar</p>
          </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
a {
  text-decoration: none;
}
.our-services {
  width: 100%;
  /* height: 400px; */
  display: flex;
  justify-content: center;
  padding: 30px 0 ;
  margin:  80px 0;
}
.services-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.services-head {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin: 30px 0;
  width: 70%;
  margin: auto;
}
.services-head > h1 {
  font-size: 3em;
  margin: 20px 0;
  font-family: 'Varela Round',sans-serif;
  font-weight: 700;
}
.services-head > p {
  font-size: 17px;
  margin: 20px 0;
  text-align: center;
  font-family: 'Varela Round',sans-serif;
}
.linea {
  border-top: 2px solid #4064d7;
  width: 30%;
  margin: 10px 0;
}
.services-colums {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  flex-direction: row;
  margin: 80px 0;
  flex-wrap: wrap;
}
.col {
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 20%;
  font-family: 'Varela Round',sans-serif;
  font-weight: 400;
  font-size: 14px;
}
.col>img {
  width: 72px;
  margin: auto;
}
.col>p {
  color: #000000;
  font-size: 27px;
  line-height: 28px;
  text-align: center;
  margin-top: 10px;
}
@media (min-width: 320px) and (max-width: 920px) {
  .our-services {
    margin: 0;
  }
  .services-head {
    width: 90%;
  }
  .services-head > h1{
    font-size: 25px;
  }
  .services-head > p {
    font-size: 16px;
    text-align: justify;
    line-height: 30px;
  }
  .services-colums {
    margin: 20px 0;
  }
  .col {
    width: 90%;
    margin: 20px 0;
  }
  .col > p{
    font-size: 20px;
  }
}
</style>
