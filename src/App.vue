<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import '@/styles/variables.scss';

body {
  background-color: $darkgray;
  padding: 0;
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: $white;
  display: flex;
  height: 100vh;
}

a,
a:visited {
  color: $purple;
  text-decoration: none;
}

h1 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  font-size: 40px;
  margin-bottom: 0;
  color: $white;
  overflow: hidden;

  @media (min-width: 450px) {
    font-size: 45px;
  }
}

h3 {
  font-size: 18px;
  margin: 5px 0 20px 0;
  font-style: italic;
}
</style>
