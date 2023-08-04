<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import navbar from './components/navbar.vue'
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
  <navbar />

  <RouterView />

</template>
