<template>
  <div class="col-sm-6 col-md-4 col-lg-3">
    <img
      style="width: 400px"
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
