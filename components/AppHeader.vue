/* eslint-disable vue/singleline-html-element-content-newline */
<template>
  <header class="header">
    <h1 class="title">First Nuxt Site</h1>
    <nuxt-image src="#"></nuxt-image>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">About</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style>
  .header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1rem;
    padding-bottom: 1rem;
    border-bottom: 1px dotted solid black;
  }

  .header .title {
    font-size: 3rem;
    color: seagreen;
  }

  .header ul {
    display: flex;
    list-style-type: none;
  }

  .header a {
    display:inline-block;
    background: black;
    color: seagreen;
    padding: .3rem 1rem;
    margin-right: .5rem;
    text-decoration: none;
  }
</style>
