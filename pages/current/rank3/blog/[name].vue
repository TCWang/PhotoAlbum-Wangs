<template>
  <div>
    <h1>享受當下 - 鳳</h1>

    <BlogDetailHero :blog="blog" />
    <BlogBack />
  </div>
</template>

<script setup>
import blogs from "@/data/rank3blog.json";

const route = useRoute();
const name = route.params.name;

const blog = blogs.find((r) => r.title === name);
</script>

<style scoped></style>
