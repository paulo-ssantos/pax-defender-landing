<template>
  <NuxtLink :to="to" :aria-label="ariaLabel" class="flex items-center justify-center">
    <img
      src="/images/pax-defender/logo-paxdefender.svg"
      alt="PaxDefender"
      :width="width"
      :height="height"
    />
  </NuxtLink>
</template>

<script setup>
defineProps({
  to: {
    type: String,
    default: "/"
  },
  ariaLabel: {
    type: String,
    default: "PaxDefender"
  },
  width: {
    type: Number,
    default: 200
  },
  height: {
    type: Number,
    default: 50
  }
});
</script>
