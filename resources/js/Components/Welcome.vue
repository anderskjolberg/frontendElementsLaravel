<script setup>
// er import i setup script, må man ikke definere pga autodefinering
import ApplicationLogo from "@/Components/ApplicationLogo.vue";
</script>

<template>
  <div>
    <div class="p-6 sm:px-20 bg-white border-b border-gray-200">
      <div>
        <ApplicationLogo class="block h-12 w-auto" />
      </div>

      <div class="mt-8 text-2xl">Under bare rams opp frontend-elementer under</div>

      <div class="mt-6 text-gray-500"></div>
    </div>

    <div class="bg-gray-200 bg-opacity-25 grid grid-cols-1 md:grid-cols-2">

      <!-- elementer i første rad trenger ikke spesifisere border under  -->
      <div id="LeftColumnFirstRow" class="p-6 border-t border-gray-200 md:border-t-0 md:border-l">
        <div class="ml-12">
          <div class="mt-2 text-sm text-gray-500">Plass til element</div>
        </div>
      </div>
      
      <div id="RightColumnFirstRow" class="p-6 border-t border-gray-200 md:border-t-0 md:border-l">
        <div class="ml-12">
          <div class="mt-2 text-sm text-gray-500">Plass til element</div>
        </div>
      </div>
      <!-- end første rad  -->
      <!-- elementer under bør ha border i md, bare copy paste  -->
      <!-- under lager dere nye rader og setter inn komponent til element du skal vise frem  -->
      <div id="LeftColumn" class="p-6 border-t border-gray-200 md:border-t-1 md:border-l">
        <div class="ml-12">
          <div class="mt-2 text-sm text-gray-500">Plass til element</div>
        </div>
      </div>

      <div id="RightColumn" class="p-6 border-t border-gray-200 md:border-t-1 md:border-l">
        <div class="ml-12">
          <div class="mt-2 text-sm text-gray-500">Plass til element</div>
        </div>
      </div>
      <!-- end resten av rader  -->

    </div>
  </div>
</template>
