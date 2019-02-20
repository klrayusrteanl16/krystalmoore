<template>
  <main id="app">
    <header>
      <h1>Krystal<span>Moore</span></h1>
    </header>
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </nav>
    <router-view />
    <footer>
      <p>footer</p>
    </footer>
  </main>
</template>

<style lang="scss">
  #app {
    padding: 1rem;
    font-family: 'Nunito', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-size: 16px;
    color: #2c3e50;
    background-color: $primary-lightest;
    min-height: 100vh;
  }
</style>
