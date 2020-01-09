<template>
<div class="descubre">
  <div class="descubre-container">
      <div class="content">
          <p class="des-head">Descubre cómo la tecnología te ayuda a cumplir con la regulación</p>
          <p class="des-reportes">
            Reportes Compliance Mx® es la herramienta en
            línea que te ayuda a detectar errores y a
            verificar que tus reportes cumplan con la
            normativa vigente.
          </p>
        <div class="descubre-btns">
          <a href="#" class="descubre-btn">CONTRATAR</a>
          <a href="#" class="descubre-btn">DESCUBRIR</a>
        </div>
      </div>
    </div>
</div>
</template>

<style scoped lang="scss">
a {
  text-decoration: none;
}
.descubre {
  background-image: url('../../public/home-banner.jpg');
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 660px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.descubre-container {
  display: flex;
  width: 60%;
  justify-content: flex-start;
  align-items: center;
}
.content {
  width: 50%;
  margin-left: 50px;
}
.des-head {
    color:#434343;
    margin-bottom:15px;
    line-height: 60px;
    font-family: "Rubik", Sans-serif;
    font-size: 3em;
    font-weight: 700;
    letter-spacing: 0px;
}
.des-reportes {
  color: #7a7a7a;
  line-height: 30px;
  margin-bottom: 10px;
  font-family: 'Varela Round',sans-serif;
  font-size: 17px;
  font-weight: 400;
}
.descubre-btns {
  display: flex;
  justify-content: space-evenly;
  margin-top: 20px;

}
.descubre-btn {
  font-family: "Montserrat", Sans-serif;
  font-size: 0.9em;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 3px;
  color: #000000;
  border: 2px solid #000;
  border-radius: 50px;
  background-color: rgba(64,100,215,0);
  padding: 13px 25px;
  margin: 30px 0;
  transition: 0.5s;
  text-align: center;
}
.descubre-btn:hover {
  background-color: #4064d7;
  border-color:#4064d7 ;
  color:#FFF;
}
@media (min-width: 320px) and (max-width: 920px) {
  .content {
    width: 85%;
    margin: 0;
  }
  .des-head {
    font-size: 24px;
    line-height: 40px;
  }
  .descubre-container {
    width: 80%;
  }
  .descubre-btns {
    display: flex;
    flex-direction: column;
    margin-left: 30px;
  }
  .descubre-btn {
    width: 156px;
    padding: 6px 1px;
    font-size: 14px;
    margin: 10px 0;
  }
}
@media (min-width: 921px) and (max-width: 999px){
  .descubre-container {
    margin-right: 10%;
  }
  .content {
    width: 70%;
    margin: 0;
  }
}
@media (min-width: 1000px){
   .content {
    width: 70%;
    margin: 0;
  }
}
</style>
