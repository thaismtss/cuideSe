<template>
   <NuxtLink :to="href">
      <div class="border-4 border-blue rounded shadow-lg w-96 h-40 mb-8">
        <img :src="img" alt="" class="mx-auto">
        <h1 class="text-center text-xl font-medium">{{ title }}</h1>
      </div>

   </NuxtLink>
</template>

<script>
export default {
    props: [
        "href",
        "img", 
        "title"
    ]
}
</script>

<style>

</style>