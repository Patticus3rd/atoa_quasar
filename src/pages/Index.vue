<template>
  <q-page class="flex flex-center">
    <q-container class="column">
      <div class="text-center q-pa-xl">
        <transition
          appear
          enter-active-class="animated rotateIn"
          leave-active-class="animated rotateIn"
        >
          <img src="../assets/logo.svg" alt="logo" key="logo" class="q-pa-sm">
        </transition>
        <h1 class="uppercase q-mb-xs">atoa</h1>
        <h3 class="q-mt-xs">Building a more wholesome community</h3>
        <div>
          <q-btn color="secondary" text-color="tertiary" outline class="q-ma-lg">Learn More</q-btn>
        </div>
      </div>
    </q-container>
  </q-page>
</template>
<style>
</style>

<script>
export default {
  name: 'PageIndex'
}
</script>
