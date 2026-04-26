<template>
  <div class="site-wrapper">
    <header class="navbar">
      <div class="navbar-inner container">
        <NuxtLink to="/" class="navbar-brand">
          <img src="/logo.svg" alt="Elektro-Glaser Logo" class="navbar-logo" />
        </NuxtLink>
        <nav class="navbar-nav" :class="{ open: menuOpen }">
          <NuxtLink to="/" class="nav-link" @click="menuOpen = false">Startseite</NuxtLink>
          <NuxtLink to="/about" class="nav-link" @click="menuOpen = false">Über uns</NuxtLink>
          <NuxtLink to="/services" class="nav-link" @click="menuOpen = false">Dienstleistungen</NuxtLink>
          <NuxtLink to="/blog" class="nav-link" @click="menuOpen = false">Blog</NuxtLink>
          <NuxtLink to="/contact" class="nav-link" @click="menuOpen = false">Kontakt</NuxtLink>
        </nav>
        <a href="mailto:info@e-glaser.de" class="navbar-mail" aria-label="E-Mail senden">✉</a>
        <button class="navbar-burger" :aria-expanded="menuOpen" @click="menuOpen = !menuOpen">
          <span></span><span></span><span></span>
        </button>
      </div>
    </header>

    <main class="main-content">
      <slot />
    </main>

    <footer class="site-footer">
      <div class="footer-inner container">
        <span>© 2025 Elektro-Glaser GmbH · Erlangen</span>
        <nav class="footer-nav">
          <NuxtLink to="/impressum">Impressum</NuxtLink>
          <NuxtLink to="/datenschutz">Datenschutz</NuxtLink>
        </nav>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
const menuOpen = ref(false)
</script>
