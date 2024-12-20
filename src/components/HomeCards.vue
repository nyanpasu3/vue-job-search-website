<script setup>
import { RouterLink } from "vue-router";
import Card from "@/components/Card.vue";
</script>

<template>
  <section class="py-4 bg-gray-950">
    <div class="container-xl lg:container m-auto bg-gray-950">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-4 p-4 rounded-lg">
        <Card>
          <h2 class="text-2xl font-bold">test test test</h2>
          <p class="mt-2 mb-4">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur
            similique hic, temporibus, dignissimos adipisci eaque ullam aliquid
            molestiae illum ipsum reiciendis maiores voluptate eius. Dolore quod
            aperiam error expedita neque?
          </p>
          <RouterLink
            to="/jobs"
            class="inline-block bg-black text-white rounded-lg px-4 py-2 hover:bg-gray-700"
          >
            Search
          </RouterLink>
        </Card>
        <Card bg="bg-sky-950">
          <h2 class="text-2xl font-bold"><3</h2>
          <p class="mt-2 mb-4">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure,
            perspiciatis pariatur recusandae eaque architecto autem molestias,
            omnis cum ratione vitae tenetur minima reiciendis doloribus tempora
            corporis quia optio ut. Omnis.
          </p>
          <RouterLink
            to="/jobs/add"
            class="inline-block bg-green-500 text-white rounded-lg px-4 py-2 hover:bg-green-600"
          >
            Add
          </RouterLink>
        </Card>
      </div>
    </div>
  </section>
</template>
