<template>
  <main>いんでっくす</main>
</template>
<script setup lang="ts">
console.log("セットアップ");
import { createApp } from "vue";
import Oruga from "@oruga-ui/oruga-next";
import "@oruga-ui/oruga-next/dist/oruga.css";

createApp({}).use(Oruga);
</script>