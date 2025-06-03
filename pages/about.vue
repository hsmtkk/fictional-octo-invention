<template>
  <Container>
    <Hero title="About" subtitle="About development activities" />
    <figure>
      <NuxtImg src="/about.jpg" alt="" sizes="sm:100vw" />
    </figure>
    <TwoColumn>
      <TwoColumnMain>
        <PostBody>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas aperiam vero dignissimos tempore amet deleniti
            repudiandae aut laudantium, distinctio numquam corporis, eum recusandae ipsum nihil, laborum magni delectus
            dolorem atque!
          </p>
          <h2>モノづくりで目指していること</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas aperiam vero dignissimos tempore amet deleniti
            repudiandae aut laudantium, distinctio numquam corporis, eum recusandae ipsum nihil, laborum magni delectus
            dolorem atque!
          </p>
          <h3>新しいことへのチャレンジ</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas aperiam vero dignissimos tempore amet deleniti
            repudiandae aut laudantium, distinctio numquam corporis, eum recusandae ipsum nihil, laborum magni delectus
            dolorem atque!
          </p>
        </PostBody>
      </TwoColumnMain>
      <TwoColumnSidebar>
        <Contact />
      </TwoColumnSidebar>
    </TwoColumn>
  </Container>
</template>

<script lang="ts" setup>
import TwoColumnSidebar from '~/components/TwoColumnSidebar.vue';


</script>

<style></style>