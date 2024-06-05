<script setup>
useSeoMeta({
  title: "Albert Code",
  description: "Développeur freelance on Vue JS",
});
</script>

<template>
  <div class="Main">
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
