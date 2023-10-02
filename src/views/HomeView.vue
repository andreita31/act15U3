<script setup>
import MovieCard from '../components/MovieCard.vue';
</script>

<template>
  <main>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
    <MovieCard img="https://image.tmdb.org/t/p/w500/1E5baAaEse26fej7uHcjOgEE2t2.jpg" title="Título jivhg gvytvytfytf yf6rffytfy tfutg7ygug7g7g7g7yguyguyg 6u gu gy"></MovieCard>
  </main>
</template>

<style>
  main{
    gap: 1.5em;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    max-width: 960px;
    margin: auto;
  }
</style>