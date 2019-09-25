<template>
<nav class="navbar sticky-top navbar-expand-sm bg-light text-dark">
    <div class="container">
        <router-link to="/" class="navbar-brand"><img src="../assets/images/logo.gif" alt=""></router-link>
        <ul class="navbar-nav ml-auto navbar_hover_color">
        <li class="nav-item"><router-link class="nav-link text-dark" to="/">Home</router-link></li>
        <li class="nav-item"><router-link class="nav-link text-dark" to="/about">Om företaget</router-link></li>
        <li class="nav-item"><router-link class="nav-link text-dark" to="/manufacturing">Tillverkning</router-link></li>
        <li class="nav-item"><router-link class="nav-link text-dark" to="/refs">Referenser</router-link></li>
        <li class="nav-item"><router-link class="nav-link text-dark" to="/partners">Partners</router-link></li>
        <li class="nav-item"><router-link class="nav-link text-dark" to="/work">Arbeta hos oss</router-link></li>
        <li class="nav-item"><router-link class="nav-link text-dark" to="/contact">Kontakt</router-link></li>
        </ul>
    </div>
</nav>
</template>

<script>
export default {

}
</script>

<style>
    .navbar_hover_color:hover {
        filter: brightness(50%)
    }
</style>
