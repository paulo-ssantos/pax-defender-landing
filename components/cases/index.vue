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
      class="grid grid-cols-1 sm:grid-cols-4 lg:grid-cols-2 gap-12 md:gap-24 my-12 px-4 sm:p-0"
    >
      <div
        class="group transition-all duration-300 hover:shadow-2xl rounded-3xl bg-white hover:scale-110 overflow-hidden"
      >
        <!-- Top Section: Icon & Detailed Description -->
        <div
          class="h-60 w-full bg-gray-100 transition-all duration-300 rounded-t-3xl flex flex-col items-center justify-center group-hover:bg-yellow-50"
        >
          <!-- Icon shrinks on hover and changes color -->
          <Icon
            name="mdi:airplane-clock"
            size="5rem"
            class="animate-pulse transition-all duration-300 group-hover:scale-75 mt-20 group-hover:-mt-8 text-yellow-600 group-hover:text-gray-700"
          />
          <!-- Detailed description fades in on hover -->
          <p
            class="mt-4 mx-4 text-gray-700 text-center opacity-0 transition-all duration-300 group-hover:opacity-100"
          >
            Se aterrou com um atraso superior a 3 horas, estamos prontos para
            auxiliá-lo a obter até 600 € de compensação.
          </p>
        </div>

        <!-- Card Content -->
        <div class="space-y-3 p-5 border border-gray-200 rounded-b-3xl">
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-semibold">Atrasos de Voos</p>
          </div>
        </div>
      </div>

      <div
        class="group transition-all duration-300 hover:shadow-2xl rounded-3xl bg-white hover:scale-110 overflow-hidden"
      >
        <!-- Top Section: Icon & Detailed Description -->
        <div
          class="h-60 w-full bg-gray-100 transition-all duration-300 rounded-t-3xl flex flex-col items-center justify-center group-hover:bg-yellow-50"
        >
          <!-- Icon shrinks on hover and changes color -->
          <Icon
            name="mdi:airplane-remove"
            size="5rem"
            class="animate-pulse transition-all duration-300 group-hover:scale-75 mt-20 group-hover:-mt-8 text-yellow-600 group-hover:text-gray-700"
          />
          <!-- Detailed description fades in on hover -->
          <p
            class="mt-4 mx-4 text-gray-700 text-center opacity-0 transition-all duration-300 group-hover:opacity-100"
          >
            Pode ter direito a até 600 € de compensação e ao reembolso de
            quaisquer despesas decorrentes dessa situação.
          </p>
        </div>

        <!-- Card Content -->
        <div class="space-y-3 p-5 border border-gray-200 rounded-b-3xl">
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-semibold">Cancelamentos</p>
          </div>
        </div>
      </div>

      <div
        class="group transition-all duration-300 hover:shadow-2xl rounded-3xl bg-white hover:scale-110 overflow-hidden"
      >
        <!-- Top Section: Icon & Detailed Description -->
        <div
          class="h-60 w-full bg-gray-100 transition-all duration-300 rounded-t-3xl flex flex-col items-center justify-center group-hover:bg-yellow-50"
        >
          <!-- Icon shrinks on hover and changes color -->
          <Icon
            name="mdi:airplane-settings"
            size="5rem"
            class="animate-pulse transition-all duration-300 group-hover:scale-75 mt-20 group-hover:-mt-8 text-yellow-600 group-hover:text-gray-700"
          />
          <!-- Detailed description fades in on hover -->
          <p
            class="mt-4 mx-4 text-gray-700 text-center opacity-0 transition-all duration-300 group-hover:opacity-100"
          >
            Se o seu voo perdeu uma ligação, pode ser elegível para compensação
            não apenas pelo tempo perdido, mas também por despesas que tenham
            ocorrido.
          </p>
        </div>

        <!-- Card Content -->
        <div class="space-y-3 p-5 border border-gray-200 rounded-b-3xl">
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-semibold">Perdas de Ligação</p>
          </div>
        </div>
      </div>

      <div
        class="group transition-all duration-300 hover:shadow-2xl rounded-3xl bg-white hover:scale-110 overflow-hidden"
      >
        <!-- Top Section: Icon & Detailed Description -->
        <div
          class="h-60 w-full bg-gray-100 transition-all duration-300 rounded-t-3xl flex flex-col items-center justify-center group-hover:bg-yellow-50"
        >
          <!-- Icon shrinks on hover and changes color -->
          <Icon
            name="mdi:airplane-alert"
            size="5rem"
            class="animate-pulse transition-all duration-300 group-hover:scale-75 mt-20 group-hover:-mt-8 text-yellow-600 group-hover:text-gray-700"
          />
          <!-- Detailed description fades in on hover -->
          <p
            class="mt-4 mx-4 text-gray-700 text-center opacity-0 transition-all duration-300 group-hover:opacity-100"
          >
            Se lhe foi negado o embarque devido a overbooking, pode
            qualificar-se para compensação e também para o reembolso de
            quaisquer despesas adicionais relacionadas.
          </p>
        </div>

        <!-- Card Content -->
        <div class="space-y-3 p-5 border border-gray-200 rounded-b-3xl">
          <div class="flex items-center justify-between font-poppins">
            <p class="text-gray-700 font-semibold">Overbooking</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
