<template>
  <div
    v-if="destination"
    class="flex items-center rounded-lg bg-white shadow-lg overflow-hidden"
  >
    <img
      class="h-32 w-32 flex-shrink-0"
      :src="`/static/img/${destination.imageUrl}`"
      :alt="destination.imageAlt"
    />
    <div class="px-6 py-4">
      <h3 class="text-lg font-semibold text-gray-800">
        {{ destination.city }}
      </h3>

      <p class="text-gray-600">
        ${{ destination.averagePrice }} / night average
      </p>
      <div class="mt-4">
        <a
          href="#"
          class="text-indigo-600 hover:text-indigo-500 font-semibold text-sm"
          >Explore {{ destination.propertyCount }} properties</a
        >
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  destination: {
    type: Object,
    require: true,
  },
});
</script>
