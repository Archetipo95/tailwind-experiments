<script setup></script>

<template>
  <div
    class="px-10 min-h-screen bg-purple-100 flex justify-center items-center"
  >
    <div
      class="relative h-[712px] w-[350px] bg-black rounded-[60px] shadow-xl overflow-hidden border-[14px] border-black"
    >
      <img
        src="../../static/iphone-rainbow.jpeg"
        alt
        class="absolute inset-0 h-full w-full object-cover"
      />
      <div class="absolute top-0 inset-x-0">
        <div
          class="relative h-6 w-40 mx-auto bg-black rounded-b-3xl flex justify-center items-center"
        >
          <div class="h-1 w-10 bg-gray-900 rounded-3xl"></div>
          <div class="absolute right-10 h-2 w-2 bg-gray-900 rounded-full"></div>
        </div>
      </div>
      <div class="relative">
        <div class="mt-2 mr-5 flex justify-end space-x-1">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4 text-white"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M2 11a1 1 0 011-1h2a1 1 0 011 1v5a1 1 0 01-1 1H3a1 1 0 01-1-1v-5zM8 7a1 1 0 011-1h2a1 1 0 011 1v9a1 1 0 01-1 1H9a1 1 0 01-1-1V7zM14 4a1 1 0 011-1h2a1 1 0 011 1v12a1 1 0 01-1 1h-2a1 1 0 01-1-1V4z"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4 text-white"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              fill-rule="evenodd"
              d="M17.778 8.222c-4.296-4.296-11.26-4.296-15.556 0A1 1 0 01.808 6.808c5.076-5.077 13.308-5.077 18.384 0a1 1 0 01-1.414 1.414zM14.95 11.05a7 7 0 00-9.9 0 1 1 0 01-1.414-1.414 9 9 0 0112.728 0 1 1 0 01-1.414 1.414zM12.12 13.88a3 3 0 00-4.242 0 1 1 0 01-1.415-1.415 5 5 0 017.072 0 1 1 0 01-1.415 1.415zM9 16a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z"
              clip-rule="evenodd"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-4 w-4 text-white"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M2 5a2 2 0 012-2h7a2 2 0 012 2v4a2 2 0 01-2 2H9l-3 3v-3H4a2 2 0 01-2-2V5z"
            />
            <path
              d="M15 7v2a4 4 0 01-4 4H9.828l-1.766 1.767c.28.149.599.233.938.233h2l3 3v-3h2a2 2 0 002-2V9a2 2 0 00-2-2h-1z"
            />
          </svg>
        </div>
        <div class="h-0.5 w-10 bg-white mr-7 ml-auto mt-1.5 rounded"></div>
        <div class="mt-2 flex flex-col items-center">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-8 w-8 text-white"
            viewBox="0 0 20 20"
            fill="currentColor"
          >
            <path
              d="M10 2a5 5 0 00-5 5v2a2 2 0 00-2 2v5a2 2 0 002 2h10a2 2 0 002-2v-5a2 2 0 00-2-2H7V7a3 3 0 015.905-.75 1 1 0 001.937-.5A5.002 5.002 0 0010 2z"
            />
          </svg>
          <p class="mt-3 text-white text-6xl font-extralight">9:41</p>
          <p class="mt-1 text-white text-lg font-light">Monday, June 7</p>
        </div>
        <div class="mt-4 mx-2 relative">
          <div
            class="absolute -bottom-4 inset-x-0 h-full bg-white/10 backdrop-blur-md rounded-2xl scale-[0.85] origin-bottom"
          ></div>
          <div
            class="absolute -bottom-2 inset-x-0 h-full bg-white/30 backdrop-blur-md rounded-3xl scale-95 origin-bottom shadow-sm"
          ></div>
          <div class="p-4 bg-white/40 backdrop-blur-md rounded-3xl shadow-sm">
            <div class="flex justify-between">
              <div>
                <p class="text-xs font-bold">9:30 AM</p>
                <h2 class="text-lg font-bold">Your Morning Summary</h2>
              </div>
              <span
                class="bg-gray-500 h-8 w-8 rounded-full text-white flex justify-center items-center"
                >11</span
              >
            </div>
            <div class="mt-2 grid grid-cols-2 gap-2">
              <div>
                <img
                  class="rounded-lg"
                  src="../../static/surf-sunset.jpeg"
                  alt
                />
                <h3 class="mt-2 text-xs font-bold leading-tight">
                  Surfing: heals the soul, kills the ribs
                </h3>
                <p class="mt-1 text-xs">
                  It's all fun and thrills until you get sucked over the falls.
                </p>
              </div>
              <div>
                <img class="rounded-lg" src="../../static/basket.jpeg" alt />
                <h3 class="mt-2 text-xs font-bold leading-tight">
                  The NBA Finals are here!
                </h3>
                <p class="mt-1 text-xs">
                  Bucks vs Suns is shaping up to be a very intriguing series!
                </p>
              </div>
            </div>
            <hr class="mt-4 border-black/20" />
            <div class="mt-3 grid grid-cols-3 gap-1 items-end">
              <div class="col-span-2">
                <h3 class="text-sm font-bold">More Updates</h3>
                <p class="mt-0.5 text-xs">Amazon, Google, Apple and Tesla</p>
              </div>
              <ul class="flex flex-row-reverse space-x-reverse -space-x-4">
                <li>
                  <img
                    class="h-8 w-8 object-fill rounded-xl"
                    src="../../static/google.png"
                    alt
                  />
                </li>
                <li>
                  <img
                    class="h-8 w-8 object-fill rounded-xl"
                    src="../../static/tesla.jpeg"
                    alt
                  />
                </li>
                <li>
                  <img
                    class="h-8 w-8 object-fill rounded-xl"
                    src="../../static/apple.png"
                    alt
                  />
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="absolute bottom-0 inset-x-0 h-20">
        <div class="flex justify-between px-10">
          <button class="bg-gray-800/40 rounded-full backdrop-blur-md p-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                d="M11 3a1 1 0 10-2 0v1a1 1 0 102 0V3zM15.657 5.757a1 1 0 00-1.414-1.414l-.707.707a1 1 0 001.414 1.414l.707-.707zM18 10a1 1 0 01-1 1h-1a1 1 0 110-2h1a1 1 0 011 1zM5.05 6.464A1 1 0 106.464 5.05l-.707-.707a1 1 0 00-1.414 1.414l.707.707zM5 10a1 1 0 01-1 1H3a1 1 0 110-2h1a1 1 0 011 1zM8 16v-1h4v1a2 2 0 11-4 0zM12 14c.015-.34.208-.646.477-.859a4 4 0 10-4.954 0c.27.213.462.519.476.859h4.002z"
              />
            </svg>
          </button>
          <button class="bg-gray-800/40 rounded-full backdrop-blur-md p-2">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-6 w-6 text-white"
              viewBox="0 0 20 20"
              fill="currentColor"
            >
              <path
                fill-rule="evenodd"
                d="M4 5a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V7a2 2 0 00-2-2h-1.586a1 1 0 01-.707-.293l-1.121-1.121A2 2 0 0011.172 3H8.828a2 2 0 00-1.414.586L6.293 4.707A1 1 0 015.586 5H4zm6 9a3 3 0 100-6 3 3 0 000 6z"
                clip-rule="evenodd"
              />
            </svg>
          </button>
        </div>
      </div>
      <div class="absolute bottom-1 inset-x-0">
        <div class="mx-auto h-1 w-28 bg-white rounded"></div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
