<template>
  <div class="row g-1">
    <AlbumCard v-for="photo in photos" :key="photo.id" :photo="photo" />
  </div>
</template>

<script setup>
import photos from "@/data/rank3album.json";
</script>

<style scoped></style>
