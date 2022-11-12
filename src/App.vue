<template>
  <div id="app">
    <NavBar :logo="logo_src" :alt="app_name" />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';

export default {
  components: {
    NavBar,
    Footer
  },
  data(){
    return{
      logo_src: "/img/logo.png",
      app_name: "Make your Burger"
    }
  }
}
</script>

<style>

* {
  font-family: Helvetica;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  --bg-cinza-principal: #222;
  --bg-amarelo-principal: #FCBA03;
  --bg-cinza-secundario: #111;
  --bg-branco: #fff;
}
#app {
  width: 100%;
  height: 100vh;
}
.main-container {
  margin: 50px;
  min-height: 250px;
}

h1 {
  font-size: 42px;
  margin-bottom: 30px;
  color: var(--bg-cinza-principal);
}

</style>
