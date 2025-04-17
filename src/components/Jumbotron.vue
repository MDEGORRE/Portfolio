<template>
    <section id="home" class="bg-center bg-[url('world-wide-web-7109276_1920.jpg')] bg-blend-multiply">
        <div class="px-4 mx-auto max-w-screen-xl text-center py-24 lg:py-56">
            <img src="../assets/20240320_125955_miniature.png" class="mt-3 mx-auto rounded-full scale-75 grayscale" alt="Photo de profile de Michaël Degorre">
            <h1 id="element" class="mb-4 text-4xl font-extrabold tracking-tight leading-none text-white md:text-5xl lg:text-6xl"></h1>
            <h2 class="text-white"></h2>
            <div class="flex flex-col space-y-4 sm:flex-row sm:justify-center sm:space-y-0">
                <a href="#" class="inline-flex justify-center items-center py-3 px-5 text-base font-medium text-center text-white rounded-lg bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900">
                    Get started
                    <svg class="w-3.5 h-3.5 ms-2 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 10">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 5h12m0 0L9 1m4 4L9 9"/>
                    </svg>
                </a>
                <a href="files/CV_FR.pdf" target="_blank" class="inline-flex justify-center hover:text-gray-900 items-center py-3 px-5 sm:ms-4 text-base font-medium text-center text-white rounded-lg border border-white hover:bg-gray-100 focus:ring-4 focus:ring-gray-400" download="CV_Michael_Degorre.pdf">
                    CV
                </a>  
            </div>
        </div>
    </section>
</template>

<script setup>
import TypeIt from 'typeit';
import { onMounted } from 'vue';

onMounted(() => {
    new TypeIt("#element", {
      strings: ["Bonjour !", "Je suis Michaël Degorre.", "<span class='text-emerald-500'>Développeur web.</span>"],
      afterComplete: function(instance) {
        instance.cursor.hidden = true
  },
    }).go();
});
</script>