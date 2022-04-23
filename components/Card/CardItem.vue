<template>
  <div>
    <nuxt-link class="title-task mb-1" :to="'app/detail/' + articles.id">
      <div class="card mb-4">
        <div class="card-body text-center">
          {{ articles.title }}
        </div>
      </div>
    </nuxt-link>
  </div>
</template>
<script>
export default {
  props: {
    articles: Object,
  },
};
</script>
<style>
.title-task {
  text-decoration: none;
}
</style>