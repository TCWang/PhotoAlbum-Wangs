<template>
  <div class="col-md-6 col-lg-4 mb-4">
    <img
      style="width: 300px"
      :src="`https://azeyrfyjaiokmhihskfh.supabase.co/storage/v1/object/public/AlbumImage/rank3/album/${photo.figure}`"
      alt=""
      class="img-fluid"
    />
  </div>
</template>

<script setup>
const props = defineProps({
  photo: Object,
});
</script>

<style scoped></style>
