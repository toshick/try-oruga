<template>
  <NuxtPage />
</template>
<script lang="ts">
import { createApp } from "vue";
import Oruga from "@oruga-ui/oruga-next";
import "@oruga-ui/oruga-next/dist/oruga.css";

createApp({}).use(Oruga);
</script>