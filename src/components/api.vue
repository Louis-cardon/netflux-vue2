<template>

</template>

<script>
export default {
  name: "api",
  data: function () {
    return {
      posts: [],
    };
  },
  methods: {
    async getData() {
      try {
        let response = await fetch("https://api.themoviedb.org/3//discover/movie?api_key=dbecf4484fc3bc26467fc17d1023c86b&language=fr-FR&page=1");
        response = await response.json();
        this.posts = response.results;
        console.log(this.posts);
      } catch (error) {
        console.log(error);
      }
    },
  },
  created() {
    this.getData();
  },
}
</script>

<style scoped>

</style>