<script setup lang="ts">
const store = useStore()
</script>
<template>
  <div class="bg-gray-950 h-screen flex">
    <div class="w-1/2 bg-neutral-950 "></div>
    <div class="w-1/2 bg-blue-600"></div>
    <div class="absolute w-screen h-screen flex items-center justify-center flex-col">
      <div class="h-screen flex items-center justify-center flex-col max-w-7xl w-4/5">
        <div class="flex "> 
        </div>
        <div class="flex items-center justify-center w-2/6 flex-col">
          <img src="../../public/img/car.png" class="w-full h-full mr-5">
          <p class="font-semmibold text-white text-xl text-center">
            A nova equipe que veio pra ficar no mundo do automobilismo. Nascida no ano de 2023, a Proton Corse é a equipe de Formula SAE representante da Universidade do Vale do Paraíba, e chegou para mostrar que trabalho duro traz grande resultado no final das contas.
          </p>
        </div>
        <div></div>
      </div>

    </div>
    <!--https://www.youtube.com/watch?v=x7nUNyToGbw-->
  </div>
</template>
