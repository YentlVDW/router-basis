<template>
    <nav class="app-header">
        <h1>
            Beau-tique
        </h1>
        <div class="nav-groep">
            <router-link to="/" exact>Home</router-link>
            <router-link to="/producten">Producten</router-link>
            <router-link to="/over">Over ons</router-link>
            <router-link to="/contact">Contact</router-link>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style>
.app-header{
    display: flex;
    justify-content: space-between;
    background-color: #40B782;
    height: 6.0rem;
    align-items: center;
    padding: 0 3rem;
    color: white;
}
.nav-groep a{
    margin: 0 1.5rem;
    text-transform: uppercase;
    font-weight: bold;
    color: #8fD5B5;
    transition: color 0.3s;
}
.nav-groep a:hover{
    color: white;
}
.nav-groep a.router-link-active{
    color: white;
}
</style>
