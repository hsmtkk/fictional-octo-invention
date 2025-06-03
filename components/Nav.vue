<template>
  <nav>
    <ul :class="styles.list">
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/about">About</NuxtLink></li>
      <li><NuxtLink to="/blog/">Blog</NuxtLink></li>
    </ul>
  </nav>
</template>

<script lang="ts" setup>
import styles from "@/styles/nav.module.css";
</script>

<style>

</style>