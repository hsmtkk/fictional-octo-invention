<template>
  <header>
    <Container large>
      <div :class="styles.flexContainer">
        <Logo boxOn/>
        <Nav/>
      </div>
    </Container>
  </header>
</template>

<script lang="ts" setup>
import styles from "@/styles/header.module.css";
</script>

<style>

</style>