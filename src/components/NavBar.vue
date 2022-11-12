<template>
  <nav>
    <rounter-link to="/" id="logo-url">
        <img :src="logo" alt="alt" id="logo">
    </rounter-link>
    <router-link to="/">Home</router-link>
    <router-link to="/pedidos">Pedidos</router-link>
  </nav>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'NavBar',
    props: ["logo", "alt"]
})
</script>

<style scoped> 
nav {
    background: var(--bg-cinza-principal);
    border-bottom: 4px solid var(--bg-cinza-secundario);
    padding: 15px 50px;
    display: flex;
    justify-content: flex-end;
    align-items: center;
}

#logo-url {
    margin: auto;
    margin-left: 0;
}

nav #logo {
    width: 40px;
    height: 40px;
}

nav a {
    color: var(--bg-amarelo-principal);
    text-decoration: none;
    margin: 12px;
    transition: .5s;
}

nav a:hover {
    color: var(--bg-branco);
}
</style>