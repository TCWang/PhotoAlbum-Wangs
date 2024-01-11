<template>
  <div class="row">
    <BlogCard v-for="blog in blogs" :key="blog.id" :blog="blog" />
  </div>
</template>

<script setup>
const props = defineProps({
  blogs: Array,
});
</script>

<style scoped></style>
