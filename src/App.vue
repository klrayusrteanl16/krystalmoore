<template>
  <main id="app">
    <header>
      <h1>Krystal<span>Moore</span></h1>
      <nav>
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </nav>
    </header>
    <router-view />
    <footer>
      <p>footer</p>
    </footer>
  </main>
</template>

<style lang="scss">

</style>
