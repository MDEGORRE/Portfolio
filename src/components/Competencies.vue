<template>

<section id="competences" class="my-3 mx-auto px-2 max-w-5xl">

    <h2 class="text-4xl py-2 text-center mb-3 font-extrabold dark:text-white">Compétences</h2>

    <div class="grid grid-cols-1 place-items-center items-stretch auto-rows-fr md:grid-cols-2 gap-4">
        <div class="block w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
            <h3 class="mb-2 text-2xl text-center font-bold tracking-tight text-gray-900 dark:text-white">Front-end</h3>
            <ul class="space-y-4 text-left text-gray-500 dark:text-gray-400">
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10 hover:scale-120 " src="../assets/HTML5_logo_black.svg" alt="HTML 5 logo">
                    <span>HTML 5</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/CSS3_logo_and_wordmark.svg" alt="CSS 3 logo">
                    <span>CSS 3</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/Bootstrap_logo.svg" alt="Bootstrap logo">
                    <span>Bootstrap</span>
                </li>    
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/tailwindcss-mark.d52e9897.svg" alt="Tailwind CSS logo">
                    <span>Tailwind CSS</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/JavaScript-logo.png" alt="Javascript logo">
                    <span>JavaScript</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/vue.svg" alt="Vue 3 logo">
                    <span>Vue 3 / Nuxt 3</span>
                </li>
            </ul>
        </div>

        <div class="block w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
            <h3 class="mb-2 text-2xl text-center font-bold tracking-tight text-gray-900 dark:text-white">Back-end</h3>
            <ul class="space-y-4 text-left text-gray-500 dark:text-gray-400">
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/PHP-logo.svg" alt="PHP logo">
                    <span>PHP</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/symfony_dynamic_02.svg" alt="Symfony logo">
                    <span>Symfony</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/Laravel.png" alt="Laravel logo">
                    <span>Laravel</span>
                </li>
            </ul>
        </div>
        
        <div class="block w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
            <h3 class="mb-2 text-2xl text-center font-bold tracking-tight text-gray-900 dark:text-white">Bases de données</h3>
            <ul class="space-y-4 text-left text-gray-500 dark:text-gray-400">
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <svg class="w-10 h-10 text-gray-800 dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12 7.205c4.418 0 8-1.165 8-2.602C20 3.165 16.418 2 12 2S4 3.165 4 4.603c0 1.437 3.582 2.602 8 2.602ZM12 22c4.963 0 8-1.686 8-2.603v-4.404c-.052.032-.112.06-.165.09a7.75 7.75 0 0 1-.745.387c-.193.088-.394.173-.6.253-.063.024-.124.05-.189.073a18.934 18.934 0 0 1-6.3.998c-2.135.027-4.26-.31-6.3-.998-.065-.024-.126-.05-.189-.073a10.143 10.143 0 0 1-.852-.373 7.75 7.75 0 0 1-.493-.267c-.053-.03-.113-.058-.165-.09v4.404C4 20.315 7.037 22 12 22Zm7.09-13.928a9.91 9.91 0 0 1-.6.253c-.063.025-.124.05-.189.074a18.935 18.935 0 0 1-6.3.998c-2.135.027-4.26-.31-6.3-.998-.065-.024-.126-.05-.189-.074a10.163 10.163 0 0 1-.852-.372 7.816 7.816 0 0 1-.493-.268c-.055-.03-.115-.058-.167-.09V12c0 .917 3.037 2.603 8 2.603s8-1.686 8-2.603V7.596c-.052.031-.112.059-.165.09a7.816 7.816 0 0 1-.745.386Z"/>
                    </svg>
                    <span>Requêtes SQL</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/mariadb_vertical-logo_black.svg" alt="MariaDB logo">
                    <span>MariaDB</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/Laravel.png" alt="Laravel">
                    <span>Modélisation</span>
                </li>
            </ul>
        </div>

        <div class="block w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-sm hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
            <h3 class="mb-2 text-2xl text-center font-bold tracking-tight text-gray-900 dark:text-white">Outils</h3>
            <ul class="space-y-4 text-left text-gray-500 dark:text-gray-400">
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10 hover:scale-120 " src="../assets/vscode.svg" alt="Visual Studio Code logo">
                    <span>Visual Studio Code</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/Git-Icon-1788C.svg" alt="Git logo">
                    <span>Git / Github</span>
                </li>
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/figma_icon.svg" alt="Figma logo">
                    <span>Figma</span>
                </li>    
                <li class="flex items-center space-x-3 rtl:space-x-reverse">
                    <img class="w-10 h-10" src="../assets/trello-logo-gradient-neutral.svg" alt="Trello logo">
                    <span>Trello</span>
                </li>
            </ul>
        </div>
    </div>

</section>

</template>