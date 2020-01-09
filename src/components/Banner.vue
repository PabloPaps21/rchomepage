<template>
  <div class="banner">
    <p>Somos especialistas en el Cumplimiento Regulatorio ante la CNBV</p>
    <a href="#" class="banner-btn">Contáctanos</a>
  </div>
</template>
<style lang="scss" scoped>
a {
  text-decoration: none;
}
.banner{
  padding: 60px 0;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background-color: #3350ac;
  color: #ffffff;
}
.banner > p {
  width: 35%;
  font-size: 40px;
  font-weight: 500;
  text-align: center;
  font-family: 'Varela Round',sans-serif;
}
.banner-btn {
  font-family: "Montserrat", Sans-serif;
  font-size: 0.9em;
  font-weight: 500;
  text-transform: uppercase;
  color: #ffffff;
  border: 2px solid #FFF;
  background-color: rgba(64,100,215,0);
  border-radius: 50px 50px 50px 50px;
  padding: 15px 30px;
  transition: 0.3s;
}
.banner-btn:hover {
  color:#4064d7;
  background-color: #FFF;
}
@media (min-width: 320px) and (max-width: 920px) {
  .banner {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    padding: 50px 0;
  }
  .banner > p {
    font-size: 18px;
    width: 80%;
    line-height: 25px;
    margin-bottom: 15px;
  }
  .banner-btn {
    padding: 10px 30px;
  }
}
</style>
