<template>
  <div :class="styles.flexContainer">
    <div :class="styles.text">
      <h1 :class="styles.title">{{title}}</h1>    
      <p :class="styles.subtitle">{{ subtitle }}</p>
      <figure v-if="imageOn">[画像]</figure>
    </div>
  </div>
</template>

<script lang="ts" setup>
import styles from "@/styles/hero.module.css";

interface Props {
  title: string;
  subtitle: string;
  imageOn?: boolean;
}

const props = withDefaults(defineProps<Props>(), {
  imageOn: false,
}) ;
</script>
