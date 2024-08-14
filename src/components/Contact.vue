<template>
    <div id="contact" class="relative bg-[#5DBABE] w-full overflow-hidden min-h-[40vh]">
      <div class="flex flex-col lg:flex-row items-start gap-4 max-w-screen-xl mx-auto px-4 py-5">
        <!-- Container para o texto -->
        <div class="w-full lg:w-1/2 p-4 flex flex-col justify-center">
          <div class="border-t-4 border-black w-[10%] mb-4"></div>
          <h2 class="uppercase font-sans mt-0 text-base sm:text-lg md:text-xl lg:text-2xl xl:text-3xl tracking-widest text-black font-bold mb-0 text-left">contato</h2>
          <p class="font-sans text-md mb-4 lg:mt-5">
            Av. Goiás, 62 - Jd. Goiás<br>
            Goiânia, GO - 7777777 
          </p>      
          <p class="font-sans text-md mb-4 lg:mt-5">
            Tel: (62) 33333-3333
            <br>
            Tel: (62) 99999-9999
          </p>
          <p class="font-sans text-md mb-4 lg:mt-5">
            info@gustavocoach62.com
          </p>
        </div>
        <!-- Container para o formulário -->
        <div class="w-full lg:w-1/2 p-4 flex flex-col justify-center relative">
          <form action="/enviar-email" method="POST" class="space-y-4">
            <div class="mb-4">
              <label for="name" class="block text-base md:text-lg font-medium mb-2 border-b-2 border-black">Nome</label>
              <input type="text" id="name" name="name" class="w-full p-2 border-2 border-black bg-transparent rounded" required />
            </div>
            <div class="mb-4">
              <label for="email" class="block text-base md:text-lg font-medium mb-2 border-b-2 border-black">E-mail</label>
              <input type="email" id="email" name="email" class="w-full p-2 border-2 border-black bg-transparent rounded" required />
            </div>
            <div class="mb-4">
              <label for="message" class="block text-base md:text-lg font-medium mb-2 border-b-2 border-black">Mensagem</label>
              <textarea id="message" name="message" rows="4" class="w-full p-2 border-2 border-black bg-transparent rounded" required></textarea>
            </div>
            <!-- Botão posicionado no canto inferior direito -->
            <button type="submit" class="absolute right-4 bg-black text-white p-2 border-2 border-black rounded hover:bg-[#5DBABE]">
              Enviar
            </button>
          </form>
        </div>
      </div>
    </div>
  </template>
  