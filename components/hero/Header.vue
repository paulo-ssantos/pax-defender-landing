<script setup>
import Logo from "../global/Logo.vue";
import { ref } from "vue";
import { Dialog, DialogPanel } from "@headlessui/vue";
import { XMarkIcon } from "@heroicons/vue/24/outline";

const mobileMenuOpen = ref(false);
</script>

<template>
  <div
    class="p-5 sm:px-16 sm:py-6 flex items-center w-full justify-between font-poppins"
  >
    <Logo />
    <div class="hidden lg:flex items-center space-x-10">
      <ul class="flex items-center space-x-12">
        <li><NuxtLink to="#our-services">Nossos Serviços</NuxtLink></li>
        <li><NuxtLink to="#compensation-cases">Casos de Compensação</NuxtLink></li>
        <li><NuxtLink to="#how-works">Como Funciona</NuxtLink></li>
      </ul>
      <ul class="flex items-center space-x-8">
        <li>
          <NuxtLink to="#cta-form" class="border-2 rounded-lg px-3 py-2 border-gray-900"
            >Preencher Agora</NuxtLink
          >
        </li>
      </ul>
    </div>
    <button
      class="lg:hidden block"
      @click="mobileMenuOpen = true"
      aria-label="hamburger-button"
    >
      <Icon name="icon-park-outline:hamburger-button" class="w-6 h-auto" />
    </button>

    <Dialog
      as="div"
      class="lg:hidden"
      @close="mobileMenuOpen = false"
      :open="mobileMenuOpen"
    >
      <div class="fixed inset-0 z-50" />
      <DialogPanel
        class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-white px-6 py-6 sm:max-w-sm sm:ring-1 sm:ring-gray-900/10"
      >
        <div class="flex items-center justify-between">
          <a href="#" class="-m-1.5 p-1.5">
            <span class="sr-only">PaxDefender</span>
            <Logo />
          </a>
          <button
            type="button"
            class="-m-2.5 rounded-md p-2.5 text-gray-700"
            @click="mobileMenuOpen = false"
            aria-label="close"
          >
            <span class="sr-only">Close menu</span>
            <XMarkIcon class="h-6 w-6" aria-hidden="true" />
          </button>
        </div>
        <div class="mt-6 flow-root">
          <div class="-my-6 divide-y divide-gray-500/10">
            <div class="space-y-2 py-6">
              <NuxtLink
                to="#our-services"
                class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                >Nossos Serviços</NuxtLink
              >
              <NuxtLink
                to="#compensation-cases"
                class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                >Casos de Compensação</NuxtLink
              >
              <NuxtLink
                to="#how-works"
                class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                >Como Funciona</NuxtLink
              >
              <NuxtLink
                to="#cta-form"
                class="-mx-3 block rounded-lg px-3 py-2 text-base font-semibold leading-7 text-gray-900 hover:bg-gray-50"
                >Preencher Agora</NuxtLink
              >
            </div>
          </div>
        </div>
      </DialogPanel>
    </Dialog>
  </div>
</template>
