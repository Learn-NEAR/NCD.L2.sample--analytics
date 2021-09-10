<template>
  <Header/>
  <section class="mt-4 md:mt-16">
        <div class="container mx-auto px-6">
            <info-banner/>
            <div class="my-8">
                <p class="text-gray-900">
                    The Dataset contract - representing individual datasets contained in their own accounts . <br>
                    The Analytics contract - responsible for creating and managing several dataset contracts. <br>
                    The users are interacting with the Analytics contract.
                </p>
            </div>
            <h3 class="text-2xl font-medium text-gray-900">Make your choose</h3>
            <div class="mt-4 grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6 md:gap-y-0">
                <div class="gradient-interact rounded-lg shadow-lg px-6 py-8 ">
                    <h2 class="text-gray-900 text-lg">Interact to Dataset contract</h2>
                    <a href="#" class="btn mt-8">Interact</a>
                </div>
                <div class="gradient-interact rounded-lg shadow-lg px-6 py-8 ">
                    <h2 class="text-gray-900 text-lg">Interact to Analytics contract</h2>
                    <a href="#" class="btn mt-8">Interact</a>
                </div>
            </div>
        </div>
  </section>
  <popular-datasets/>
</template>

<script>
import Header from '@/components/Header.vue'
import InfoBanner from '@/components/InfoBanner.vue'
import PopularDatasets from '@/components/PopularDatasets.vue'
export default {
  components: { 
      Header,
      InfoBanner,
    PopularDatasets,

      },

}
</script>

<style>

</style>