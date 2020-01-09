<template>
  <section class="list">
    <img src="../../public/people.jpg" alt="tech">
    <div class="lista">
      <ul>
        <li>Democratiza el uso de la tecnología orientada al cumplimiento regulatorio</li>
        <li>Reduce tempo, esfuerzo y costos</li>
        <li>Aporta más transparencia en la información del SFM</li>
        <li>Impulsa mejoras en productos y servicios</li>
        <li>Fomenta mayor inclusión financiera</li>
      </ul>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.list {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  padding: 50px 0;
  margin: 30px 0;
}
.list > img {
  margin-left: 70px;
  max-width: 570px;
}
ul > li {
  color: #7a7a7a;
  line-height: 50px;
  font-family: 'Varela Round',sans-serif;
  font-weight: 500;
}
@media (min-width: 320px) and (max-width: 920px) {
  .list {
    display: flex;
    flex-direction: column;
  }
  .lista {
    margin-top: 10px;
    width: 80%;
    justify-content: space-evenly;
    font-size: 20px;
  }
  .list > img {
    margin-left: 0;
    max-width: 266px;
  }
  .list > ul {
    width: 80%;
  }
  ul >li {
    font-size: 16px;
    margin: 20px 0;
    line-height: 30px;
  }
}
@media (min-width: 921px) and (max-width: 999px) {
 .list > img {
    max-width: 40%;
  }
  .lista {
    width: 40%;
    justify-content: space-evenly;
    font-size: 20px;
  }
}
@media (min-width: 1000px) {
  .list > img {
    max-width: 40%;
  }
  .lista {
    width: 40%;
    justify-content: space-evenly;
    font-size: 23px;
  }
}
</style>
