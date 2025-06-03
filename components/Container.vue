<template>
  <div v-if="large" :class="styles.large">
    <slot/>
  </div>
  <div v-else :class="styles.default">
    <slot/>
  </div>
</template>

<script lang="ts" setup>
import styles from "@/styles/container.module.css";

interface Props {
  large?: boolean;
}

const props = withDefaults(defineProps<Props>(), {
  large: false,
}) ;


</script>

<style>

</style>