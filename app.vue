<template>
  <div class="max-w-3xl px-4 mx-auto">
   <!-- Header -->
    <header class="mt-8 mb-4 flex justify-between items-end">
      <div>
        <NuxtLink to="/" class="text-2xl font-semibold">Personal Blog</NuxtLink>
        <p class="text-gray-500">Learn programming easily</p>
      </div>

    <Btn>Contact Me</Btn>
    </header>
    <!-- ./Header -->
     <!-- Main Content -->
      <NuxtPage/>
     <!-- ./Main Content -->
  </div>
</template>


<style>
body {
 @apply bg-gray-100;
}
</style>