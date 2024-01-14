<template>
  <div class="row">
    <AlbumCard v-for="photo in photos" :key="photo.id" :photo="photo" />
  </div>
</template>

<script setup>
import photos from "@/data/rank3album.json";
</script>

<style scoped></style>
