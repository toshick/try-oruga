<template>
  <main class="container max-w-2xl mx-auto my-30 p-3 bg-gray-100 rounded">
    <h1 class="text-bold text-gray-700">いんでっくす</h1>
    <ul class="flex flex-wrap justify-center">
      <li v-for="(u, index) in 6" :key="`user${index}`" class="p-2">
        <User />
      </li>
    </ul>
    <button class="btn-blue">なにかのボタン</button>
  </main>
</template>
<script lang="ts">
console.log("セットアップ");
</script>