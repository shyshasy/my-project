  <template>
    <div id="app">
      <AppNavbar />
      <AppJumbotron />
      <AppCTA />
      <AppCards />
      <AppFooter />
    </div>
  </template>

  <script>
  import AppNavbar from './components/Navbar.vue'; // Updated import
  import AppJumbotron from './components/Jumbotron.vue';
  import AppCTA from './components/CTA.vue';
  import AppCards from './components/Cards.vue';
  import AppFooter from './components/Footer.vue';
  export default {
    name: 'App',
    components: {
      AppNavbar, // Updated component name
      AppJumbotron,
      AppCTA,
      AppCards,
      AppFooter
    },
  };
  </script>

  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  </style>