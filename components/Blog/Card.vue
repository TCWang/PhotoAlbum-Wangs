<template>
  <div class="col-md-6 col-lg-4 mb-4">
    <div class="card">
      <div class="bg-image hover-overlay">
        <NuxtImg
          class="img-fluid img-thumbnail"
          :src="`https://azeyrfyjaiokmhihskfh.supabase.co/storage/v1/object/public/AlbumImage/rank3/blog20231219/${blog.figure}`"
          alt=""
          @click="navigateTo(`/current/rank3/blog/${blog.title}`)"
        />
      </div>
    </div>
    <div class="cord-body">
      <h3>{{ blog.id }} - {{ blog.title }}</h3>
      <p>{{ blog.date }} - {{ blog.place }}</p>

      <NuxtLink
        :href="`/current/rank3/blog/${blog.title}`"
        class="btn btn-primary px-4"
        >閱讀</NuxtLink
      >
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  blog: Object,
});
</script>

<style scoped></style>
