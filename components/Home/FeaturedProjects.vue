<template>
  <div>
    <Header2>
      FEATURED PROJECTS
    </Header2>
    <div class="space-y-4">
      <AppProjectCard v-for="(project, id) in projects" :key="id" :project="project" />
    </div>
    <div class="flex items-center justify-center mt-6 text-sm">
      <UButton label="All Projects &rarr;" to="/projects" variant="link" color="gray" />
    </div>
  </div>
</template>

<script lang="ts" setup>
import Header2 from '../App/headers/Header2.vue';

const { data: projects } = await useAsyncData("projects-home", () =>
  queryContent("/projects").where({ featured: true }).limit(3).find()
);
</script>
