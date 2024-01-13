<template>
  <div>
    <h1>生活隨筆 內文</h1>
    <!-- <NuxtImg
      class="img-fluid"
      :src="`https://azeyrfyjaiokmhihskfh.supabase.co/storage/v1/object/public/AlbumImage/rank3/blog20231219/${blog.figure}`"
      alt=""
    /> -->

    <h3>{{ blog.title }}</h3>

    <div v-html="blog.content"></div>
  </div>
</template>

<script setup>
const props = defineProps({
  blog: Object,
});
</script>

<style scoped></style>
