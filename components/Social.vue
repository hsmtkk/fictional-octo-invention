<template>
  <ul :class="styles.list">
    <li>
      <NuxtLink to="https://twitter.com">
        <Icon name="entypo-social:twitter" />
      </NuxtLink>
      <NuxtLink to="https://www.facebook.com">
        <Icon name="entypo-social:facebook" />
      </NuxtLink>
      <NuxtLink to="https://github.com">
        <Icon name="octicon:mark-github-16" />
      </NuxtLink>
    </li>
  </ul>
</template>

<script lang="ts" setup>
import styles from "@/styles/social.module.css";
</script>

<style></style>