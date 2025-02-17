<script setup></script>

<template>
  <section class="p-6 sm:p-20 sm:-mt-32 font-poppins">
    <div
      class="grid grid-cols-1 sm:grid-cols-2 items-center gap-20 md:gap-16 lg:gap-20 mb-8"
    >
      <div class="space-y-8">
        <p class="capitalize font-semibold text-gray-600">Fácil e Rápido</p>
        <h2 class="text-[#14183E] font-bold text-4xl sm:text-5xl font-volkhov">
          Um Processo Simples em 4 Passos Fáceis
        </h2>
        <div class="space-y-8">
          <div
            class="flex space-x-4 group hover:scale-110 transition-all duration-300"
          >
            <div
              class="opacity-70 bg-blue-500 rounded-xl hover:bg-blue-600 transition-all duration-300 hover:scale-110 group-hover:rotate-45 flex items-center justify-center w-12 h-12"
            >
              <Icon
                name="mdi:numeric-1"
                class="opacity-100 w-12 h-auto text-white group-hover:-rotate-45 transition-all duration-300"
              />
            </div>
            <div>
              <p class="text-gray-600 font-bold">Conte Sua História</p>
              <p class="text-sm text-gray-600">
                Preencha nosso formulário rápido com detalhes do seu voo
                problemático.
              </p>
            </div>
          </div>

          <div
            class="flex space-x-4 group hover:scale-110 transition-all duration-300"
          >
            <div
              class="opacity-80 group bg-blue-500 rounded-xl hover:bg-blue-600 transition-all duration-300 group-hover:scale-110 group-hover:rotate-45 flex items-center justify-center w-12 h-12"
            >
              <Icon
                name="mdi:numeric-2"
                class="opacity-100 w-12 h-auto text-white group-hover:-rotate-45 transition-all duration-300"
              />
            </div>

            <div>
              <p class="text-gray-600 font-bold">Análise Especializada</p>
              <p class="text-sm text-gray-600">
                Nossa equipe analisa gratuitamente as chances de sua
                compensação.
              </p>
            </div>
          </div>
          <div
            class="flex space-x-4 group hover:scale-110 transition-all duration-300"
          >
            <div
              class="opacity-90 bg-blue-500 rounded-xl hover:bg-blue-600 transition-all duration-300 group-hover:scale-110 group-hover:rotate-45 flex items-center justify-center w-12 h-12"
            >
              <Icon
                name="mdi:numeric-3"
                class="opacity-100 w-12 h-auto text-white group-hover:-rotate-45 transition-all duration-300"
              />
            </div>

            <div>
              <p class="text-gray-600 font-bold">Acompanhamento Transparente</p>
              <p class="text-sm text-gray-600">
                Mantenha-se informado sobre cada etapa do processo em tempo
                real.
              </p>
            </div>
          </div>
          <div
            class="flex space-x-4 group hover:scale-110 transition-all duration-300"
          >
            <div
              class="bg-blue-500 rounded-xl hover:bg-blue-600 transition-all duration-300 group-hover:scale-110 group-hover:rotate-45 flex items-center justify-center w-12 h-12"
            >
              <Icon
                name="mdi:numeric-4"
                class="opacity-100 w-12 h-auto text-white group-hover:-rotate-45 transition-all duration-300"
              />
            </div>

            <div>
              <p class="text-gray-600 font-bold">Receba Sua Compensação</p>
              <p class="text-sm text-gray-600">
                Depositado diretamente na sua conta sem estresse adicional.
              </p>
            </div>
          </div>
        </div>
      </div>
      <nuxt-picture
        src="/images/bookings.jpg"
        alt="bookings"
        class="-mt-16 sm:mt-0"
        width="314"
        height="457"
        sizes="sm:100vw md:50vw lg:400px"
      />
    </div>
  </section>
</template>
