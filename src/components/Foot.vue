<template>
  <div class="footerC">
    <div class="footer-container">
      <div class="footer-col">
        <div class="somos">
          <img src="/logo.png" alt="logo">
          <p>Somos una compañía mexicana que brinda
            servicios de asesoría a entidades financieras
            con el objetivo de asegurar que se cumpla con
            la información regulatoria consistente y oportunamente.
          </p>
        </div>
      </div>
      <div class="footer-col">
        <div class="autoridades">
          <h2>AUTORIDADES</h2>
          <a href="#" class="foot-visited">
            <div class="aut-img">
              <img src="/SHCP_Icon-150x150.png" alt="">
              <div class="texto">
                <p>SHCP</p>
              </div>
            </div>
          </a>
          <a href="#" class="foot-visited">
          <div class="aut-img">
            <img src="/BANXICO.png" alt="">
            <div class="texto">
              <p>BANXICO</p>
            </div>
          </div>
          </a>
          <a href="#" class="foot-visited">
          <div class="aut-img">
            <img src="/cnbv1-150x150.png" alt="">
            <div class="texto">
              <p>CNBV</p>
            </div>
          </div>
          </a>
          <a href="#" class="foot-visited">
          <div class="aut-img">
            <img src="/IPAB_Icon-150x150.png" alt="">
            <div class="texto">
              <p>IPAB</p>
            </div>
          </div>
          </a>
          <a href="#" class="foot-visited">
          <div class="aut-img">
            <img src="/CONDUSEF_Icon-150x150.png" alt="">
            <div class="texto">
              <p>CONDUSEF</p>
            </div>
          </div>
          </a>
        </div>
      </div>

      <div class="footer-col">
        <div class="contacto">
          <h2>CONTACTO</h2>
          <p>Benito Juárez, Col. del Valle, 03100 CDMX, México</p>
          <p class="correo">contacto@reportescompliance.mx</p>
        </div>
      </div>
      <div class="footer-col">
        <div class="ubicacion">
          <h2>UBICACIÓN</h2>
          <!-- <img src="/mapa.png" alt="mapa"> -->
          <div class="mapa-footer">
            <div class="gmap_canvas">
              <iframe  width="219" height="170" class="mapa_canvas"
              src="https://maps.google.com/maps?q=Benito%20Ju%C3%A1rez%2C%20Col.%20del%20Valle%2C%2003100%20CDMX%2C%20M%C3%A9xico&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0">
              </iframe>
              <!-- Google Maps Generator by <a href="https://www.embedgooglemap.net">embedgooglemap.net</a> -->
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="last">
      <p>Copyright © 2020 Reportes Compliance Mx ® | Powered by Reportes Compliance Mx ®</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
a {
 text-decoration: none;
}
  .footerC {
  background-color:#3a3a3a;
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  color:#FFF;
  padding: 30px 0;
  align-items: flex-start;
  width:100%;
}
.footer-container {
  width: 80%;
  display: flex;
  justify-content: center;
  align-items: flex-start;
}
.footer-col{
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 20%;
}
.somos {
  display: flex;
  flex-direction: column;
}
.somos > p {
  margin: 30px 0;
  font-size:14px;
  line-height: 30px;
  text-align: justify;
  font-weight: 400;
  font-family: 'Varela Round',sans-serif;
}
.somos > img {
  max-width: 270px;
}
.autoridades {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.autoridades > h2 {
  margin-bottom: 15px;
  font-weight: 300;
  font-family: 'Varela Round',sans-serif;
  font-weight: 400;
  font-size: 20px;
}
.contacto {
  display: flex;
  justify-content: center;
  flex-direction: column;
  width: 100%;
}
.contacto > h2 {
  font-family: 'Varela Round',sans-serif;
  font-weight: 400;
  font-size: 20px;
}
.contacto > p {
  margin: 30px 0;
  font-size: 14px;
  text-align: justify;
  font-family: 'Varela Round',sans-serif;
  font-weight: 400;
}
.ubicacion {
  display: flex;
  flex-direction: column;
}
.ubicacion > h2 {
  font-family: 'Varela Round',sans-serif;
  font-weight: 400;
  font-size: 20px;
}
.mapa-footer {
  margin-top: 20px;
}
.ubicacion > img {
  margin-top: 30px;
  max-width: 260px;
}
.mapouter {
  position:relative;
  text-align:right;
  height:170px;
  width:300px;
}
.mapa_canvas {
  overflow:hidden;
  background:none!important;
  height:170px;
  width:300px;
}
.aut-img {
  display:flex;
  flex-direction: row;
  justify-content: space-between;
  margin: 10px 0;
  align-items: center;
}
.aut-img > img{
  max-width: 30px;
}
.texto {
  font-family: 'Varela Round',sans-serif;
  font-size: 14px;
  font-weight: 400;
}
.texto {
  display: flex;
  justify-content: flex-start;
  margin-left: 30px;
  width: 90%;
  color: #FFF;
}
.foot-visited > a:visited {
  color: #FFF;
}
.last {
  display: flex;
  justify-content: center;
  width: 100%;
  border-top: 1px solid#545454;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #FFF;
  font-size: 18px;
  background-color:#3a3a3a;
  height: 70px;
  margin-top: 10px;
  padding-top: 20px;
}
@media (min-width: 320px) and (max-width: 920px) {
   .footer-container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
  }
  .footer-col {
    width: 100%;
    display: flex;
    justify-content: center;
  }
  .somos {
    display: flex;
    justify-content: center;
    padding: 0 30px;
    width: 80%;
  }
  .somos > img {
    margin: auto;
  }
  .contacto {
    display: flex;
    justify-content: center;
    text-align: center;
    margin-top: 30px;
    width: 80%;
  }
  .contacto > p {
    display: flex;
    justify-content: center;
    padding: 0 20px;
    font-size: 14px;
  }
  .correo {
    margin: 10px 0;
    font-size: 11px !important;
    line-height: 30px;
    text-align: justify;
    font-weight: 400;
    font-family: 'Varela Round',sans-serif;
  }
  .ubicacion {
    display: flex;
    justify-content: center;
    text-align: center;
  }
  .last > p {
    font-size: 16px;
    padding: 0 50px;
  }
}
@media (min-width: 921px) and (max-width: 999px) {
  .footer-container {
    width: 90%;
    padding: 0 20px;
    justify-content: space-evenly;
    flex-wrap: wrap;
  }
  .somos {
    display: flex;
    flex-direction: column;
    width: 95%;
  }
  .contacto {
    width: 95%;
  }
  .mapa-footer {
    max-width: 185px;
  }
  .footer-col {
    width: 20%;
  }
  .correo {
    margin: 10px 0;
    font-size: 11px !important;
    line-height: 30px;
    text-align: justify;
    font-weight: 400;
    font-family: 'Varela Round',sans-serif;
  }
}
@media (min-width: 1000px) {
  .footer-container {
    width: 80%;
    padding: 0 20px;
    justify-content: space-evenly;
    flex-wrap: wrap;
  }
  .footer-col {
    width: 20%;
  }
  .mapa-footer{
    max-width: 185px;
  }
  .somos {
    display: flex;
    flex-direction: column;
    width: 95%;
  }
  .somos > p {
    margin: 10px 0;
    padding: 0 10px;
    font-size: 14px;
    line-height: 30px;
    text-align: justify;
    font-weight: 400;
    font-family: 'Varela Round',sans-serif;
  }
  .correo {
    margin: 10px 0;
    font-size: 11px !important;
    line-height: 30px;
    text-align: justify;
    font-weight: 400;
    font-family: 'Varela Round',sans-serif;
  }
}
</style>
