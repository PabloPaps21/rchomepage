<template>
  <div id="app">
   <!--<div id="nav">
      <router-link to="/">Home</router-link>
    </div> -->
     <div class="header">
      <div class="header-container">
        <img src="../public/logo.png" alt="logo" class="img-logo">
          <div class="header-btns">
            <a href="#" class="btn-sesion">Iniciar Sesión</a>
          </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #FFF;
    }
  }
}
a {
  text-decoration: none;
}
.header {
  display: flex;
  height: 101px;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  padding: 0 20px;
  border-top: 1px solid#eaeaea;
  border-bottom: 1px solid #eaeaea;
}
.header-container {
  width: 63%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.img-logo {
  max-width: 297px;
}
.btn-sesion {
  border-radius: 50px;
  font-family: 'Varela Round',sans-serif;
  font-size: 14px;
  padding: 14px 40px;
  color: #ffffff;
  border-color: #4064d7;
  background-color: #4064d7;
  font-weight: 400;
  transition: 0.5s;
}
.btn-sesion:hover {
  background-color: #3a3a3a;
  color:#FFF;
}
@media (min-width: 320px) and (max-width: 920px) {
  .header {
    height: 80px;
  }
 .header-container{
    width: 100%;
  }
  .img-logo {
    width:40%;
  }
  .btn-sesion {
    padding: 4px 11px;
  }

}
@media (min-width: 921px) and (max-width: 999px) {
  .header-container {
    width: 90%;
  }
  .img-logo {
    width:45%;
  }
}
@media (min-width: 1000px) {
  .header-container {
    width: 90%;
  }
}
</style>
