<script setup>
import Hero from "~/components/hero/index.vue";
import Services from "~/components/services/index.vue";
import Cases from "~/components/cases/index.vue";
import How from "~/components/how/index.vue";
import Testimonials from "~/components/testimonials/index.vue";
import Companies from "~/components/companies/index.vue";
import Subscribe from "~/components/subscribe/index.vue";
</script>

<template>
  <LazyHero />
  <LazyServices />
  <LazyCases />
  <LazyHow />
  <LazyTestimonials />
  <LazyCompanies />
  <LazySubscribe />
</template>
