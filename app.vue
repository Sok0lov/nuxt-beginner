<template>
  <div class="p-8">
    <NuxtLayout >
      <Header class="mb-8">
        <ul>
          <li>
            <NuxtLink class="mr-3" to="/">Home</NuxtLink>
            <NuxtLink to="/events">Events</NuxtLink>
          </li>
        </ul>
      </Header>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup lang="ts">
</script>