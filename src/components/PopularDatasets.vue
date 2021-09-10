<template>
  <section class="mt-8">
        <div class="container mx-auto px-6">
            <h3 class="text-2xl font-medium text-gray-900">Popular datasets</h3>
            <div class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-6 my-6 gap-x-4 xl:gap-x-12 gap-y-6 relative">
                <dataset/>
                <dataset/>
                <dataset/>
                <dataset/>
                <dataset/>
                <dataset/>
                <dataset/>
                <dataset/>
                <dataset/>
            </div>
        </div>
    </section>
</template>

<script>
import Dataset from './Dataset.vue'
export default {
  components: { Dataset },

}
</script>

<style>

</style>