<template>
  <div class="containerP">
    <div class="columnas">
      <div class="somos">
        <img src="/logo.png" alt="logo">
        <p>Somos una compañía mexicana que brinda
            servicios de asesoría a entidades financieras
            con el objetivo de asegurar que se cumpla con
            la información regulatoria consistente y oportunamente.
        </p>
      </div>
    </div>
    <div class="columnas">
      <h2>AUTORIDADES</h2>
      <div class="offi">
              <a href="#">
        <div class="auth">
          <img src="/SHCP_Icon-150x150.png" alt="SHCP">
          <div class="texto">
            <p>SHCP</p>
          </div>
        </div>
      </a>
      <a href="#">
        <div class="auth">
          <img src="/BANXICO.png" alt="BANXICO">
          <div class="texto">
            <p>BANXICO</p>
          </div>
        </div>
      </a>
      <a href="#">
        <div class="auth">
          <img src="/cnbv1-150x150.png" alt="CNVB">
          <div class="texto">
            <p>CNBV</p>
          </div>
        </div>
      </a>
      <a href="#">
        <div class="auth">
          <img src="/IPAB_Icon-150x150.png" alt="IPAB">
          <div class="texto">
            <p>IPAB</p>
          </div>
        </div>
      </a>
      <a href="#">
        <div class="auth">
          <img src="/CONDUSEF_Icon-150x150.png" alt="CONDUSEF">
          <div class="texto">
            <p>CONDUSEF</p>
          </div>
        </div>
      </a>
      </div>
    </div>
    <div class="columnas">
      <h2>CONTACTO</h2>
      <div class="direccion">
        Benito Juárez,
        Col. del Valle, 03100
        CDMX, México
      </div>
      <div class="correo">
        contacto@reportescompliance.mx
      </div>
    </div>
    <div class="columnas">
      <h2>UBICACIÓN</h2>
      <div class="mapa-footer">
        <div class="gmap_canvas">
          <iframe  width="219" height="170" class="mapa_canvas"
          src="https://maps.google.com/maps?q=Benito%20Ju%C3%A1rez%2C%20Col.%20del%20Valle%2C%2003100%20CDMX%2C%20M%C3%A9xico&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0">
          </iframe>
          <!-- Google Maps Generator by <a href="https://www.embedgooglemap.net">embedgooglemap.net</a> -->
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
  a:visited {
    color: #FFF;
  }
  h2 {
    margin-top: 20px;
    font-family: 'Varela Round',sans-serif;
    color: #FFF;
  }
  .containerP {
  background-color:#3a3a3a;
  width: 100%;
  display: flex;
  justify-content: space-evenly;
  flex-wrap: wrap;
  padding: 20px 0;
  }
  .columnas {
    width: 20%;
  }
  .somos {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .somos > img {
    width: 80%;
  }
  .somos > p {
    margin-top: 30px;
    text-align: justify;
    line-height: 25px;
    font-family: 'Varela Round',sans-serif;
    color: #FFF;
  }
  .autoridades {
   width: 100%;
   display: flex;
   justify-content: center;
  font-family: 'Varela Round',sans-serif;
  }
  .auth {
    display: flex;
    flex-direction:row;
    justify-content:center;
    align-items: center;
  }
  .auth > img {
    max-width: 30px;
  }
  .offi {
    margin-top: 30px;
  }
  .texto {
    display: flex;
    justify-content: center;
    width: 45%;
    font-family: 'Varela Round',sans-serif;
  }
  .direccion {
    width: 80%;
    display: flex;
    justify-content: center;
    margin: 0 auto;
    margin-top: 30px;
    font-family: 'Varela Round',sans-serif;
    color: #FFF;
  }
  .correo {
    width: 80%;
    display: flex;
    justify-content: center;
    margin: 0 auto;
    margin-top: 30px;
    font-size: 16px;
    font-family: 'Varela Round',sans-serif;
    color: #FFF;
  }
  .mapa-footer {
    margin-top: 30px;
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
  @media (min-width: 320px) and (max-width: 649px){
    .containerP {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .columnas {
      width: 90%;
      display: flex;
      justify-content: center;
      flex-direction: column;
    }
    .somos {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    }
    .somos > img {
      width: 50%;
      margin: 0 auto;
    }
  }
  @media (min-width: 650px) and (max-width: 1000px) {
    .containerP {
      display: flex;
      flex-direction: column;
      align-items: center;
      color: #FFF;
    }
    .columnas {
      width: 65%;
      display: flex;
      justify-content: center;
      flex-direction: column;
      margin: 20px 0;
    }
    .somos {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    }
    .somos > img {
      width: 50%;
      margin: 10px  auto;
    }
    .texto {
      width: 25%;
    }
  }
</style>
