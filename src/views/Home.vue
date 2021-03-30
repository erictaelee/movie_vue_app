<template>
  <div class="home">
    <h1>{{ message }}</h1>
    <div v-for="movie in movies">
      <p>{{ movies }}</p>

    </div>

  </div>
</template>

<style>
</style>

<script>
import axios from "axios";

export default {
  data: function () {
    return {
      message: "Welcome to Vue.js!",
      movies: [],
    };
  },
  created: function () {},
  methods: {
    moviesIndex: function () {
      console.log("in movies index");
    },
  },
};
</script>
