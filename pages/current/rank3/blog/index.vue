<template>
  <div class="">
    <h1>享受當下 - 鳳</h1>
    <h2>生活隨筆</h2>

    <BlogCards
      v-if="blogsOrganized.sorted.length"
      :blogs="blogsOrganized.sorted"
    />
    <h1 v-else class="text-danger">沒有符合的部落格文章</h1>
  </div>
</template>

<script setup>
import blogs from "@/data/rank3blog.json";
const blogsOrganized = {
  sorted: [...blogs].sort((a, b) => a.date.localeCompare(b.date)),
};
</script>

<style scoped></style>
