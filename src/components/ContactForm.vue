<template>

    <section id="contact" class="max-w-4xl mx-auto px-2">
        
        <h2 class="text-4xl text-center my-3 font-extrabold dark:text-white">Contact</h2>

        <p class="my-2 text-gray-900 dark:text-white">Contactez-moi via ce formulaire. Vous pouvez aussi m'envoyer directement un 
            <a href="mailto:degorremichael@gmail.com" target="_blank" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">mail</a> ou me contacter sur 
            <a href="https://www.linkedin.com/in/micha%C3%ABl-degorre/" target="_blank" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Linkedin</a>.
        </p>

        <form action="https://formspree.io/f/xgegpgwe" method="POST">
            <div class="mb-6">
                <label for="first_name" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Prénom</label>
                <input type="text" id="first_name" name="first_name" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Votre prénom" required />
            </div>
            <div class="mb-6">
                <label for="last_name" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Nom</label>
                <input type="text" id="last_name" name="last_name" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Votre nom" required />
            </div>
            <div class="mb-6">
                <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Email</label>
                <input type="email" id="email" name="email" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Votre email" required />
            </div> 
            <div>
                <label for="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Votre message</label>
                <textarea id="message" rows="4" name="message" class="block p-2.5 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="Ecrivez le contenu de votre message..."></textarea>
            </div>
            <button type="submit" class="my-3 text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Envoyer</button>
        </form>

    </section>
</template>