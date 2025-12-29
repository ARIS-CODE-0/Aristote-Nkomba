<template>

  <body
    class="bg-background-light dark:bg-background-dark text-text-main dark:text-white font-display antialiased selection:bg-primary/20 selection:text-primary min-h-screen flex flex-col">
    <!-- Main Content Container -->
    <main class="grow flex flex-col items-center justify-center max-w-md mx-auto w-full px-6 py-12 md:py-20">
      <!-- Profile Section -->
      <div class="flex flex-col items-center w-full mb-10 animate-enter">
        <div class="relative group cursor-default">
          <div
            class="absolute -inset-0.5 bg-linear-to-r from-gray-200 to-gray-100 dark:from-gray-700 dark:to-gray-800 rounded-full blur opacity-50 group-hover:opacity-75 transition duration-500">
          </div>
          <div
            class="relative h-32 w-32 rounded-full overflow-hidden border border-gray-100 dark:border-gray-800 shadow-sm bg-gray-50 dark:bg-gray-900"
            data-alt="Aristote Nkomba"
            style='background-image: url("/Aristote-Nkomba.JPG"); background-size: cover; background-position: center;'>
          </div>
        </div>
        <h1
          class="mt-6 text-2xl font-bold tracking-tight text-center text-gray-900 dark:text-white animate-enter delay-100">
          Aristote Nkomba
        </h1>
        <h2 class="mt-2 text-base font-medium text-primary dark:text-primary/90 text-center animate-enter delay-200">
          Développeur &amp; Entrepreneur
        </h2>
      </div>
      <!-- About Section -->
      <div class="w-full max-w-xs mb-12 animate-enter delay-200">
        <p class="text-center text-gray-600 dark:text-gray-300 leading-relaxed text-sm md:text-base">
          Je développe des projets web et des solutions digitales. Intéressé par la technologie, l’automatisation et
          l’entrepreneuriat.
        </p>
      </div>
      <!-- Links Section -->
      <div class="w-full flex flex-col gap-4 animate-enter delay-300">
        <!-- LinkedIn Button -->
        <a class="group relative flex w-full items-center justify-center gap-3 rounded-lg border border-gray-200 dark:border-gray-700 bg-white dark:bg-gray-800 px-8 py-3.5 transition-all hover:border-primary/50 hover:bg-gray-50 dark:hover:bg-gray-700/50 hover:shadow-sm"
          href="https://cd.linkedin.com/in/aristote-nkomba-697b53333">
          <span
            class="material-symbols-outlined text-gray-700 dark:text-gray-300 group-hover:text-primary transition-colors text-[24px]">
            work
          </span>
          <span
            class="font-semibold text-gray-800 dark:text-gray-100 group-hover:text-primary transition-colors text-sm">
            LinkedIn
          </span>
          <span
            class="absolute right-4 opacity-0 -translate-x-2 group-hover:opacity-100 group-hover:translate-x-0 transition-all duration-300 material-symbols-outlined text-gray-400 group-hover:text-primary text-[18px]">
            arrow_forward
          </span>
        </a>
        <!-- GitHub Button -->
        <a class="group relative flex w-full items-center justify-center gap-3 rounded-lg border border-gray-200 dark:border-gray-700 bg-white dark:bg-gray-800 px-8 py-3.5 transition-all hover:border-primary/50 hover:bg-gray-50 dark:hover:bg-gray-700/50 hover:shadow-sm"
          href="https://github.com/aristote-nkomba">
          <span
            class="material-symbols-outlined text-gray-700 dark:text-gray-300 group-hover:text-primary transition-colors text-[24px]">
            code
          </span>
          <span
            class="font-semibold text-gray-800 dark:text-gray-100 group-hover:text-primary transition-colors text-sm">
            GitHub
          </span>
          <span
            class="absolute right-4 opacity-0 -translate-x-2 group-hover:opacity-100 group-hover:translate-x-0 transition-all duration-300 material-symbols-outlined text-gray-400 group-hover:text-primary text-[18px]">
            arrow_forward
          </span>
        </a>
      </div>
    </main>
    <!-- Footer -->
    <footer class="w-full py-6 text-center animate-enter delay-300">
      <a href="https://aristote-nkomba.carrd.co/" class="inline-block hover:underline">
        <p class="text-xs text-gray-400 dark:text-gray-600">
          © Aristote Nkomba
        </p>
      </a>
    </footer>
  </body>
</template>
<script setup>
  useHead({
    title: 'Aristote Nkomba - Développeur & Entrepreneur',
    meta: [
      {
        name: 'description',
        content: 'Bienvenue sur le site officiel d\'Aristote Nkomba, développeur web et entrepreneur passionné par la technologie et l\'innovation.'
      },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { charset: 'utf-8' }
    ],
    link: [
      { rel: 'icon', type: 'image/png', href: '/favicon.png' },
      { rel: 'preconnect', href: 'https://fonts.googleapis.com' },
      { rel: 'preconnect', href: 'https://fonts.gstatic.com', crossorigin: '' },
      {
        rel: 'stylesheet',
        href: 'https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght@400;500;700&display=swap'
      },
      {
        propriety: 'og:title',
        content: 'Aristote Nkomba - Développeur & Entrepreneur'
      },
      {
        propriety: 'og:description',
        content: 'Bienvenue sur le site officiel d\'Aristote Nkomba, développeur web et entrepreneur passionné par la technologie et l\'innovation.'
      },
      {
        propriety: 'og:image',
        content: 'https://aristote-nkomba.netlify.app/Aristote-Nkomba.png'
      },
      {
        propriety: 'og:type',
        content: 'website'
      },
      {
        propriety: 'og:url',
        content: 'https://aristote-nkomba.netlify.app/'
      },
      {
        rel: 'canonical',
        href: 'https://aristote-nkomba.netlify.app/'
      }
    ]
  })
</script>
