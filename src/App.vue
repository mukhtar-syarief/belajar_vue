<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-lg top-nav">
      <div class="container-fluid d-flex align-items-center justify-content-between">
        <div class="brand d-flex align-items-center">
          <img src="https://troubleshoot.id/assets/images/Newlogo/logo.png" alt="Troubleshoot" class="brand-logo d-flex justify-content-center">
          <route-link to="/" class="route">
            <a class="navbar-brand brand-title">Troubleshoot.id</a>
          </route-link>
        </div>
        <div class="collapse navbar-collapse d-flex justify-content-end" id="navbarNav">
          <ul class="navbar-nav d-flex align-items-center">
            <router-link to="/tracking" class="route">
              <li class="nav-item"> 
                <a class="nav-link route-link" aria-current="page" >LACAK PESANAN</a>
              </li>
            </router-link>
            <router-link to="/pricelist" class="route">
              <li class="nav-item">
                <a class="nav-link route-link">DAFTAR HARGA</a>
              </li>
            </router-link>
            <router-link to="/faq" class="route">
              <li class="nav-item">
                <a class="nav-link route-link">FAQ</a>
              </li>
            </router-link>
            <router-link to="/login">
              <li class="nav-item">
                <a class="btn-login btn-light">Login</a>
              </li>
            </router-link>
          </ul>
        </div>
      </div>
    </nav>
  </header>
  <RouterView />
</template>

<style>

*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Ropa Sans', sans-serif;
}

#root{
  width: 100vw;
  min-height: 100vh;
  background-color: white;
  color: black;
}


header {
  top: 0;
  margin-bottom: 36px;
}

.top-nav {
  padding: 25px 26px;
  /* width: 100vw; */
  width: 100vw;
  height: 58px;
  display: flex;
  flex-direction: row;
  background-color: rgb(247, 247, 247);
}

.brand-logo {
  width: 3.3rem;
  height: auto;
}

.brand-title {
  font-weight: bold;
  font-size: 20px;
}

a {
  padding: 8px 16px;
  font-size: 16px;
}

a:hover {
  background: none;
}

li {
  margin-left: 20px;
}

li:hover {
  background: none;
}


.route:hover {
  background: none;
}

.route {
  padding: 0;
}

.btn-login {
  background-color: #17a2b8;
  border-radius: 10px;
  padding: 12px 16px;
  color: white;
  font-family: 'Ropa Sans', sans-serif;
}



</style>
