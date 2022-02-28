<template>
    <div
        class="bg-gray-100 sm:bg-yellow-300 md:bg-green-300 lg:bg-pink-300 xl:bg-blue-300 2xl:bg-purple-300"
    >
        <div class="bg-gray-100 grid lg:grid-cols-2 2xl:grid-cols-5">
            <div
                class="px-8 py-12 max-w-md mx-auto sm:max-w-xl lg:px-12 lg:py-24 lg:max-w-full xl:mr-0 2xl:col-span-2"
            >
                <div class="xl:max-w-xl">
                    <img class="h-10" src="@/assets/img/logo.svg" alt="Worklocation" />
                    <img
                        class="mt-6 rounded-lg shadow-xl sm:mt-8 sm:h-64 sm:w-full sm:object-cover sm:object-center lg:hidden"
                        src="@/assets/img/beach-work.jpg"
                        alt="Woman worktioning on beach"
                    />
                    <h1
                        class="mt-6 text-2xl font-bold text-gray-900 sm:mt-8 sm:text-4xl lg:text-3xl xl:text-4xl"
                    >
                        You can work from anywhere.
                        <br />
                        <span class="text-indigo-500">Take advantage of it.</span>
                    </h1>
                    <p class="mt-2 text-gray-600 sm:mt-4 sm:text-xl">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur
                        doloribus earum corporis praesentium maxime distinctio eligendi
                        voluptatum delectus pariatur labore nisi neque, at voluptates
                        provident, fugiat sequi unde, dolorem facilis!
                    </p>
                    <div class="mt-4 sm:mt-6">
                        <a class="btn" href="#">Book your escape</a>
                    </div>
                </div>
            </div>
            <div class="hidden lg:block relative 2xl:col-span-3">
                <img
                    class="absolute inset-0 w-full h-full object-cover object-center"
                    src="@/assets/img/beach-work.jpg"
                    alt="Woman worktioning on beach"
                />
            </div>
        </div>

        <div class="max-w-md sm:max-w-xl lg:max-w-6xl mx-auto px-8 lg:px-12 py-8">
            <h2 class="text-xl text-gray-900">Popular destinations</h2>
            <p
                class="mt-2 text-gray-600"
            >A selection of great work-friendly cities with lots to see and explore.</p>
            <div class="mt-6 grid gap-6 lg:grid-cols-2 xl:grid-cols-3">
                <DestinationCard v-for="d in destinations" :destination="d" :key="d.city" />
            </div>
        </div>
    </div>
</template>

<script setup>
import popularDestinations from "../data/popularDestinations";
import DestinationCard from '../components/atoms/DestinationCard.vue'

import { ref } from 'vue'

const destinations = ref(popularDestinations)

</script>