<script setup>
useSeoMeta({
  title: "Albert Code",
  description: "Développeur freelance on Vue JS",
});
</script>

<template>
  <div class="Main">
    <div>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 496 512"
        class="w-12"
      >
        <path
          d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3 .3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5 .3-6.2 2.3zm44.2-1.7c-2.9 .7-4.9 2.6-4.6 4.9 .3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3 .7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3 .3 2.9 2.3 3.9 1.6 1 3.6 .7 4.3-.7 .7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3 .7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3 .7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"
        />
      </svg>
    </div>
    <!-- <div class="flex flex-col items-center justify-center">
      <div class="flex flex-col items-center justify-center py-20">
        <img src="/public/img/memoji-apple.jpg" width="300" />
        <h1 class="uppercase">Développeur</h1>
        <h1 class="uppercase">FRONT END</h1>
      </div>
      <div class="flex flex-col items-center">
        <p class="text-center">
          "À l'écoute et motivé, bonne capacité de communication et de
          proposition. Travail rendu dans les temps. <br />Je recommande
          vivement ce prestataire pour une mission front-end."
        </p>
        <p>Ehua Kassi - <em>Krypto Valley</em></p>
      </div>
      <div></div>
    </div>
    <div class="flex justify-around py-10 mx-10">
      <img
        src="/public/img/Logo_JS.svg"
        alt="JavaScript logo"
        width="60"
        title="JavaScript logo"
      />
      <img
        src="/public/img/Logo_TypeScript.svg"
        alt="TypeScript logo"
        width="60"
      />
      <img src="/public/img/Logo_Vue.js.svg" alt="Vue JS logo" width="60" />
      <img src="/public/img/Logo_Nuxt.svg" alt="Nuxt logo" width="60" />
      <img src="/public/img/Logo_React.svg" alt="React logo" width="60" />
      <img src="/public/img/Logo_NextJS.svg" alt="React logo" width="60" />
    </div> -->
    <div class="flex bg-apple-grey px-5 mb-10">
      <div class="mr-5">
        <div class="pt-10 pb-3">
          <h4 class="text-xs font-extralight">Projet</h4>
          <h2 class="text-3xl font-semibold">Pronote Football</h2>
          <h3 class="text-base font-extralight">
            Notez les joueurs de votre équipe favorite après le match.
          </h3>
        </div>
        <div class="rounded-xl overflow-hidden shadow-lg">
          <img
            src="/public/img/pronote-football-1.png"
            alt="pronote-football"
          />
        </div>
      </div>
      <div class="mr-5">
        <div class="rounded-b-xl overflow-hidden shadow-lg">
          <img
            src="/public/img/pronote-football-5.png"
            alt="pronote-football"
          />
        </div>
        <div class="pb-3">
          <h4 class="text-xs font-bold mt-4">Système de jeu dynamique</h4>
          <p class="text-xs font-extralight mt-4 text-left">
            Une fois les notes attribués aux joueurs, on peut retrouver le
            système de jeu avec les notes que l'utilisateur a attributés ainsi
            que les postes des joueurs sur le terrain, ainsi que la note globale
            de l'équipe en bas à droite.
          </p>
        </div>
      </div>
      <div class="pt-10">
        <div class="pb-3">
          <h4 class="text-xs font-bold pb-10">
            Notes moyennes des internautes
          </h4>
          <p class="text-left text-xs font-extralight pb-10">
            Maintenant que vos notes ont étés attribués, nous accedons aux notes
            moyennes des internautes qui ont aussi votés de leurs côtés. Cela
            donne les notes globales que les utilisateurs ont attribués aux
            joueurs, ainsi qu'à l'entraîneur. En bas à droite on peut aussi voir
            les
          </p>
        </div>
        <div class="rounded-t-xl overflow-hidden shadow-lg mt-20">
          <img
            src="/public/img/pronote-football-4.png"
            alt="pronote-football"
          />
        </div>
      </div>
    </div>
  </div>
</template>
