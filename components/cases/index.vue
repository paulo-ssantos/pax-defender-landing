<script setup></script>

<template>
  <section class="p-6 sm:p-20 sm:-mt-32 font-poppins" id="compensation-cases">
    <div class="text-center space-y-3 relative">
      <p class="capitalize font-semibold text-gray-600">Casos de Compensação</p>
      <h2 class="text-[#14183E] font-bold text-4xl sm:text-5xl font-volkhov">
        Recuperamos Suas Perdas em
      </h2>
      <PlusPlusSVG />
    </div>
    <div
      class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-2 gap-12 md:gap-24 my-12 px-4 sm:p-0"
    >
      <div>
        <nuxt-img
          src="https://picsum.photos/618/914?grayscale"
          alt="delayed-flight"
          class="w-full h-60 object-cover rounded-t-3xl"
        />
        <div
          class="space-y-3 p-3 border-b border-r border-l rounded-x-3xl rounded-b-3xl bg-white shadow-xl"
        >
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-medium">
              Atrasos superiores a 3 horas
            </p>
            <p class="text-gray-500 font-medium">Até $X,X</p>
          </div>
          <div class="flex items-center justify-even space-x-2">
            <span class="font-bold text-gray-700 ml-4">•</span>
            <p class="text-gray-500 font-medium">Lei XX.X</p>
          </div>
        </div>
      </div>
      <div>
        <nuxt-img
          src="https://picsum.photos/618/914?grayscale"
          alt="cancelled-flight"
          class="w-full h-60 object-cover rounded-t-3xl"
        />
        <div
          class="space-y-3 p-3 border-b border-r border-l rounded-x-3xl rounded-b-3xl bg-white shadow-xl"
        >
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-medium">Cancelamentos inesperados</p>
            <p class="text-gray-500 font-medium">Até $X,X</p>
          </div>
          <div class="flex items-center justify-even space-x-2">
            <span class="font-bold text-gray-700 ml-4">•</span>
            <p class="text-gray-500 font-medium">Lei XX.X</p>
          </div>
        </div>
      </div>
      <div>
        <nuxt-img
          src="https://picsum.photos/618/914?grayscale"
          alt="connection-lost"
          class="w-full h-60 object-cover rounded-t-3xl"
        />
        <div
          class="space-y-3 p-3 border-b border-r border-l rounded-x-3xl rounded-b-3xl bg-white shadow-xl"
        >
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-medium">Perda de conexões</p>
            <p class="text-gray-500 font-medium">Até $X,X</p>
          </div>
          <div class="flex items-center justify-even space-x-2">
            <span class="font-bold text-gray-700 ml-4">•</span>
            <p class="text-gray-500 font-medium">Lei XX.X</p>
          </div>
        </div>
      </div>
      <div>
        <nuxt-img
          src="https://picsum.photos/618/914?grayscale"
          alt="overbooking"
          class="w-full h-60 object-cover rounded-t-3xl"
        />
        <div
          class="space-y-3 p-3 border-b border-r border-l rounded-x-3xl rounded-b-3xl bg-white shadow-xl"
        >
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-medium">Situações de overbooking</p>
            <p class="text-gray-500 font-medium">Até $X,X</p>
          </div>
          <div class="flex items-center justify-even space-x-2">
            <span class="font-bold text-gray-700 ml-4">•</span>
            <p class="text-gray-500 font-medium">Lei XX.X</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
