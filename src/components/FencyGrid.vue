<template>
  <div class="grid place-items-center min-h-screen">
    <!-- Responsive Grid Layout -->
    <div
      class="p-4 max-w-5xl grid gap-4 xs:grid-cols-2 xs:p-8 md:grid-cols-4 lg:gap-6"
    >
      <h1
        class="text-4xl font-extrabold xs:col-span-2 xs:grid xs:gap-4 xs:grid-cols-2 md:col-span-3 md:text-5xl md:grid-cols-3 lg:text-6xl"
      >
        <span class="md:col-span-2">Grid layout with Tailwind CSS.</span>
      </h1>
      <p
        class="xs:row-start-2 xs:col-start-2 xs:self-center md:col-start-1 md:col-span-2 md:pr-12 md:text-lg"
      >
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio hic
        itaque alias officiis.
      </p>
      <div class="h-16 bg-blue-500 xs:h-auto xs:square"></div>
      <div class="h-16 bg-blue-500 xs:h-auto xs:square"></div>
      <div class="h-16 bg-pink-500 xs:h-auto xs:square"></div>
      <div class="h-16 bg-blue-500 xs:h-auto xs:square md:col-start-2"></div>
      <div class="h-16 bg-pink-500 xs:h-auto xs:square"></div>
      <div class="h-16 bg-blue-500 xs:h-auto xs:square"></div>
      <div class="h-16 bg-blue-500 xs:h-auto xs:square"></div>
      <div class="h-16 bg-pink-500 xs:h-auto xs:square"></div>
      <p class="self-center md:text-lg md:col-span-2 md:text-center md:px-4">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit, and some more.
      </p>
    </div>
  </div>
</template>
