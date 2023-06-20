<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/icon.png" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/contato">contato</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
  <CNavbar color-scheme="light" class="bg-light">
  <CContainer fluid>
    <CNavbarBrand href="#">
      <img src="@/assets/icon.png" alt="" width="50" height="50"/>
    </CNavbarBrand>
  </CContainer>
</CNavbar>
</template>

<style scoped>
</style>
