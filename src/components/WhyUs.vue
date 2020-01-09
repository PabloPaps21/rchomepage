<template>
  <div class="why">
    <h1>¿Por qué necesitas a Reportes Compliance MX®?</h1>
    <div class="why-linea"></div>
    <p class="testimonio">
      1,500 entidades del Sistema
      Financiero Mexicano(SMF), supervisadas
      por la CNBV, quedan vulnerables ante los
      recurrentes cambios normativos que la autoridad.
      Esto se traduce en +$340 millones de pesos por
      multas impuestas anualmente, sin mencionar el
      impacto reputacional.</p>
    <img src="/cnbv1.png" alt="CNVB">
    <p class="why-cnbv ">Comisión Nacional Bancaria y de Valores</p>
  </div>
</template>

<style lang="scss" scoped>
.why {
  background-color: #efefef;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin: 30px 0;
  font-family: 'Varela Round',sans-serif;
  font-weight: 700;
  font-size: 1em;
  padding: 50px 0;
}
.why > h1 {
  font-size: 2.8em;
  font-weight: 700;
  margin: 30px 0;
}
.testimonio {
  width: 50%;
  margin: 30px 0;
  font-size: 1.3em;
  text-align: center;
  color: #7a7a7a;
  font-weight: 500;
  line-height: 35px;
  font-family: 'Varela Round',sans-serif;
  font-weight: 500;
  font-size: 18px;
}
.why > img {
  width: 70px;
}
.why-cnbv {
  margin-top: 20px;
  color: #6ec1e4;
  margin-bottom: 30px;
  font-family: 'Varela Round',sans-serif;
  font-weight: 500;
  font-size: 14px;
}
.why-linea {
  border-top: 2px solid #4064d7;
  width: 20%;
  margin: 10px 0;
}
@media (min-width: 320px) and (max-width: 920px) {
  .why {
    margin: 10px 0;
  }
  .why > h1 {
    font-size: 25px;
    text-align: center;
    width: 90%;
  }
  .testimonio {
    width: 90%;
    text-align: justify;
  }
}
@media (min-width: 921px) and (max-width: 999px) {
  .why > h1 {
    width: 90%;
    text-align: center;
  }
}
@media (min-width: 1000px) {
   .why > h1 {
    width: 90%;
    text-align: center;
  }
}
</style>
