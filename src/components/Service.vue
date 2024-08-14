<template>
  <div id="service" class="relative min-h-[50vh]">
    <!-- Imagem de fundo -->
    <img src="../../public/img/img-2.webp" alt="imagem de fundo"
      class="w-full h-full object-cover absolute inset-0 z-0">

    <!-- Conteúdo sobreposto -->
    <div class="relative z-10 text-black px-4 py-8 max-w-screen-xl mx-auto h-full flex flex-col justify-center">
      <!-- Contêiner para o título e linha preta -->
      <div class="relative mb-12">
        <!-- Linha preta posicionada diretamente acima do h2 -->
        <div class="relative mb-5 border-t-4 border-black w-[10%] mt-5"></div>
        <h2 class="uppercase font-sans mt-0 text-base sm:text-lg md:text-xl lg:text-2xl xl:text-3xl tracking-widest text-black font-bold mb-0 text-left">COMO POSSO</h2>
        <h2 class="tuppercase font-sans mt-0 text-base sm:text-lg md:text-xl lg:text-2xl xl:text-3xl tracking-widest text-black font-bold mb-0 text-left">AJUDAR</h2>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Coluna 1 -->
        <div class="flex flex-col items-center justify-center overflow-hidden border-8 border-black bg-transparent bg-opacity-70 p-4 rounded-none text-center">
          <h3 class="uppercase font-sans mt-0 text-sm sm:text-sm md:text-sm lg:text-md xl:text-xl tracking-widest text-black font-bold mb-0 text-center border-b-4 border-black w-full max-w-[90%] mx-auto break-words">
            Apoio para <br> Casais</h3>
          <div class="flex flex-col items-center">
            <p class="text-black mt-4">1 h 30 min</p>
            <p class="text-black mt-3">R$ 120</p>
          </div>
          <div class="flex justify-center mt-5">
            <button class="bg-[#20B2AA] text-black py-2 px-6 rounded-none transition-colors duration-300 hover:bg-[#5DBABE] hover:text-black active:bg-gray-800 active:text-gray-200 focus:outline-none focus:ring-2 focus:ring-black">
              Agendar Agora
            </button>
          </div>
        </div>

        <!-- Coluna 2 -->
        <div class="flex flex-col items-center justify-center overflow-hidden border-8 border-black bg-transparent bg-opacity-70 p-4 rounded-none text-center">
          <h3 class="uppercase font-sans mt-0 text-sm sm:text-sm md:text-sm lg:text-md xl:text-xl tracking-widest text-black font-bold mb-0 text-center border-b-4 border-black w-full max-w-[90%] mx-auto break-words">
            Crescimento <br> Pessoal</h3>
          <div class="flex flex-col items-center">
            <p class="text-black mt-4">45 min</p>
            <p class="text-black mt-3">R$ 90</p>
          </div>
          <div class="flex justify-center mt-5">
            <button class="bg-[#20B2AA] text-black py-2 px-6 rounded-none transition-colors duration-300 hover:bg-[#5DBABE] hover:text-black active:bg-gray-800 active:text-gray-200 focus:outline-none focus:ring-2 focus:ring-black">
              Agendar Agora
            </button>
          </div>
        </div>

        <!-- Coluna 3 -->
        <div class="flex flex-col items-center justify-center overflow-hidden border-8 border-black bg-transparent bg-opacity-70 p-4 rounded-none text-center">
          <h3 class="uppercase font-sans mt-0 text-sm sm:text-sm md:text-sm lg:text-md xl:text-xl tracking-widest text-black font-bold mb-0 text-center border-b-4 border-black w-full max-w-[90%] mx-auto break-words">
            Coaching <br> Particular</h3>
          <div class="flex flex-col items-center">
            <p class="text-black mt-4">1 h</p>
            <p class="text-black mt-3">R$ 70</p>
          </div>
          <div class="flex justify-center mt-5">
            <button class="bg-[#20B2AA] text-black py-2 px-6 rounded-none transition-colors duration-300 hover:bg-[#5DBABE] hover:text-black active:bg-gray-800 active:text-gray-200 focus:outline-none focus:ring-2 focus:ring-black">
              Agendar Agora
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
