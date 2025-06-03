<template>
  <NuxtLink v-if="boxOn" to="/" :class="styles.box">CUBE</NuxtLink>
  <NuxtLink v-else to="/" :class="styles.basic">CUBE</NuxtLink>
</template>

<script lang="ts" setup>
import styles from "@/styles/logo.module.css";

interface Props {
  boxOn?: boolean;
}
const props = withDefaults(defineProps<Props>(), {
  boxOn: false,
}) ;
</script>

<style>

</style>