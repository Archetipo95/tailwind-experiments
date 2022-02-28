<template>
  <div class="min-h-screen flex flex-col justify-center items-center">
    <div class="mx-auto p-6">
      <div class="flex justify-center space-x-10">
        <div
          class="bg-gradient-to-tr from-blue-500 to-green-400 relative w-80 h-80 max-w-full rounded-lg shadow-2xl overflow-hidden"
        >
          <img
            class="mix-blend-overlay absolute inset-0 w-full h-full object-cover"
            src="../../static/skyscraper.jpeg"
            alt=""
          />
        </div>
        <div
          class="bg-gradient-to-tr from-yellow-500 to-red-400 relative w-80 h-80 max-w-full rounded-lg shadow-2xl overflow-hidden"
        >
          <img
            class="mix-blend-overlay absolute inset-0 w-full h-full object-cover"
            src="../../static/skyscraper.jpeg"
            alt=""
          />
        </div>
        <div
          class="bg-gradient-to-tr from-red-500 to-purple-400 relative w-80 h-80 max-w-full rounded-lg shadow-2xl overflow-hidden"
        >
          <img
            class="mix-blend-overlay absolute inset-0 w-full h-full object-cover"
            src="../../static/skyscraper.jpeg"
            alt=""
          />
        </div>
      </div>
    </div>
    <div class="min-h-screen flex flex-col justify-center items-center">
      <div
        class="relative w-full max-w-4xl h-96 bg-blue-500 rounded-xl bg-texture bg-cover bg-center bg-blend-color-burn"
      >
        <h1
          class="p-8 max-w-3xl text-8xl font-black uppercase text-white transform -rotate-6 mix-blend-overlay filter blur-px"
        >
          CSS blend modes are super cool!
        </h1>
      </div>
    </div>
  </div>
</template>
