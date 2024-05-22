<template>
  <UserDashboard />
</template>

<script>
import UserDashboard from './components/Dashboard/UserDashboard.vue'

export default {
  name: 'App',
  components: {
    UserDashboard
  }
}
</script>

<style>
@import '~primeflex/primeflex.css';
@import 'primeicons/primeicons.css';

html {
  background-color: #f6f6f6;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;

}
</style>
