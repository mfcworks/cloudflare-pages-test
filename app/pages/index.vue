<template>
  <div>
    <h1>Hello, Cloudflare Pages!</h1>
    <p class="nuxt-color">This is a test site for Cloudflare Pages with Nuxt.</p>
    <div><a href="/page1">This is `a` link to page1</a></div>
    <div><NuxtLink to="/page1">This is NuxtLink to page1</NuxtLink></div>
  </div>
</template>

<style scoped>
.nuxt-color {
  color: #00DC82;
  font-weight: bold;
}
</style>
