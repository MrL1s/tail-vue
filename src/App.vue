<template>
  <div class="header">
    <HeaderSite/>
  </div>
  <div class="glav">
    <Glav />
  </div>
  <div class="dop">
    <DopSection />
  </div>
  <div class="final">
    <FinalFooter />
  </div>
</template>

<script setup>
  import HeaderSite from './components/HeaderSite.vue'
  import Glav from './components/Glav.vue'
  import DopSection from './components/DopSection.vue'
  import FinalFooter from './components/FinalFooter.vue'
</script>