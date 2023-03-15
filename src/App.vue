<template>
  <NavBar />
  <MouseTrace />
  <router-view :key="$route.fullPath" />
</template>

<script>
import 'bootstrap/dist/css/bootstrap.min.css';
import 'bootstrap/dist/js/bootstrap.min.js';
import NavBar from './components/NavBar';
import MouseTrace from './components/MouseTrace';

export default {
  name: "App",
  components: {
    NavBar,
    MouseTrace,
  }
}

</script>

<style></style>