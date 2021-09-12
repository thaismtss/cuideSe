<template>
  <div class="flex justify-around h-screen container mx-auto px-40">
    <div class="self-center">
      <h1 class="text-blue font-poppins text-8xl ">
        cuideSe
      </h1>
    </div>
    <div class=" flex-col self-center">
      <form action="post" class="flex flex-col">
        <input type="text" value="email" class="bg-grey rounded p-4 mb-5">
        <input type="text" value="senha" class="bg-grey rounded p-4 mb-5">
        <input type="button" value="entrar" class="bg-blue rounded p-4 mb-5">
      </form>
      <NuxtLink class="text-blue" to="/cadastro">Cadastre-se</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {};
</script>
