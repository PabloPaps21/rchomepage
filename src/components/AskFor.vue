<template>
<div class="ask-for">
    <div class="ask-container">
      <div class="formulario">
        <div class="entradas">
          <div class="names">
            <label for="name">Nombre<span class="red">*</span></label>
            <input type="text" name="name">
            <label for="last-name">Apellido<span class="red">*</span></label>
            <input type="text" name="last-name">
            <label for="subject">Tema <span class="red">*</span></label>
            <input type="text" name="subject">
          </div>
          <div class="mail">
            <label for="email">Correo electrónico<span class="red">*</span></label>
            <input type="email" name="email">
            <label for="telephone">Teléfono <span class="red">*</span></label>
            <input type="text" name="telephone">
          </div>
        </div>
        <div class="mensaje">
          <p>Déjanos tu mensaje</p>
        </div>
        <div class="envia">
          <label for="send-msg">Mensaje<span class="red">*</span></label>
          <input type="text-area" name="send-msg">
          <button>Enviar Mensaje</button>
        </div>
      </div>
      <div class="cotiza">
        <h1>Solicita una cotización</h1>
        <hr class="blue-line">
        <div class="equipo">
          <p>Nuestro equipo cuenta con más de 15 años de experiencia en el sector financiero.</p>
        </div>
        <hr class="blue-line">
        <h2 class="correo-cotiza">contacto@reportescompliance.mx</h2>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.ask-for {
  display: flex;
  justify-content: space-evenly;
  width: 100%;
  padding: 70px 0;
  margin-top: 70px;
}
.ask-container {
  width: 70%;
  display: flex;
  justify-content: space-evenly;
}
.formulario {
  width: 50%;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}
.entradas {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.names {
  width: 45%;
  display: flex;
  flex-direction: column;
}
.names > label {
  font-family: 'Varela Round',sans-serif;
  font-size: 14px;
  font-weight: 700;
  text-align: left;
}
.names > input {
  /* width: 90%; */
  height: 34px;
  padding: 6px 12px;
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 2px;
  margin-bottom:30px;
  margin-top: 10px;
}
.mail {
  width: 45%;
  display: flex;
  flex-direction: column;
}
.mail > input {
  /* width: 90%; */
  height: 34px;
  padding: 6px 12px;
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 2px;
  margin-bottom:30px;
  margin-top: 10px;
}
.mail > label {
  text-align: left;
  font-family: 'Varela Round',sans-serif;
  font-size: 14px;
  font-weight: 700;
}
.cotiza {
  width: 40%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding-bottom: 140px;
}
.cotiza > h1{
  font-family: 'Varela Round',sans-serif;
  font-size: 50px;
  font-weight: 700;
  margin: 30px 0;
  width: 53%;
  text-align: center;
}
.correo-cotiza {
  display: flex;
  justify-content: center;
  font-family: 'Varela Round',sans-serif;
  font-size: 20px;
  font-weight: 500;
  margin-top: 30px;
  width: 100%;
}
.equipo {
  padding: 40px 0;
  width: 73%;
  color:#7a7a7a;
  text-align: center;
  font-family: 'Varela Round',sans-serif;
  font-size: 19px;
  font-weight: 500;
}
.blue-line {
  background-color:#4064d7;
  height: 1px;
  width: 25%;
  text-align: center;
}
.red {
  color: red;
}
.mensaje {
  display: flex;
  justify-content: flex-start;
  margin-left: 15px;
  margin-right: 15px;
  border-top: 1px solid #7a7a7a;
  border-bottom: 1px solid #7a7a7a ;
  padding: 40px 0;
  font-family: 'Varela Round',sans-serif;
  font-size: 42px;
  font-weight: 400;
}
.envia {
  margin: 30px 20px;
  display: flex;
  flex-direction: column;
}
.envia > label {
  font-family: 'Varela Round',sans-serif;
  font-size: 14px;
  font-weight: 700;
  text-align: left;
}
.envia > input {
  margin-top: 10px;
  height: 150px;
  display: flex;
  border: 1px solid #ccc;
  align-items: flex-start;
}
.envia > button {
  width: 150px;
  margin-top: 10px;
  border: 1px solid;
  border-color: #7a7a7a;
  -webkit-border-radius: 2px;
  border-radius: 2px;
  background-color: #FFF;
  padding: .6em 1em .4em;
  color: #000;
}
.envia > button:hover {
  background-color:#ccc;
}
@media (min-width: 320px) and (max-width: 920px) {
  .ask-for {
    margin-top: 1px;
  }
  .ask-container {
    display: flex;
    flex-direction: column;
    width: 90%;
  }
  .formulario {
    width: 100%;
  }
  .names, .mail {
    width: 100%;
  }
  .envia {
    margin: 30px 0px;
  }
  .mensaje {
    font-size: 25px;
    padding: 30px 0;
    border-top: 1px solid #d3d3d3;
    border-bottom: 1px solid #d3d3d3;
    color: #3a3a3a;
    text-align: center;
    display: flex;
    justify-content: center;
  }
  .cotiza {
    width: 100%;
    display: flex;
    justify-content: center;
    padding-bottom: 30px;
  }
  .cotiza > h1 {
    width: 70%;
    font-size: 25px;
    text-align: center;
    display: flex;
    justify-content: center;
  }
  .correo-cotiza {
    width: 50%;
    font-size: 16px;
    text-align: center;
  }
  .equipo > p {
    font-size: 17px;
  }
  .entradas {
    display: flex;
    flex-direction: column;
  }
}
@media (min-width: 921px) and (max-width: 999px) {
  .ask-container {
    width: 90%;
  }
}
@media (min-width: 1000px) {
  .ask-container {
    width: 90%;
  }
  .cotiza > h1 {
    width: 100%;
  }
  .names, .mail {
    width: 45%;
  }
}
</style>
