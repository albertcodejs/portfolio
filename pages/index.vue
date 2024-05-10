<script setup>
useSeoMeta({
  title: "albertcode.com | Développeur Front End",
  description: "Développeur freelance on Vue JS",
});
</script>

<template>
  <div class="Main">
    <div class="flex flex-col items-center justify-center">
      <div class="flex flex-col items-center justify-center py-20">
        <img src="/public/img/memoji-apple.jpg" width="300" />
        <h1 class="uppercase">DÉVELOPPEUR</h1>
        <h1 class="uppercase">FRONT END</h1>
      </div>
      <div class="flex flex-col items-center">
        <p class="text-center">
          "If you have everything under control, you are not moving fast
          enough."
        </p>
        <p>Mario Andrettict</p>
      </div>
      <div></div>
    </div>
    <div class="flex justify-around py-16 mx-10">
      <img
        src="/public/img/Logo_JS.svg"
        alt="JavaScript logo"
        width="60"
        title="JavaScript logo"
      />
      <img src="/public/img/Logo_Vue.js.svg" alt="Vue JS logo" width="60" />
      <img
        src="/public/img/Logo_TypeScript.svg"
        alt="TypeScript logo"
        width="60"
      />
      <img src="/public/img/Logo_Nuxt.svg" alt="Nuxt logo" width="60" />
      <img src="/public/img/Logo_React.svg" alt="React logo" width="60" />
      <img src="/public/img/Logo_NextJS.svg" alt="React logo" width="60" />
    </div>
    <div class="flex flex-col items-end mx-16 pb-10">
      <h1 class="font-bold">Moi c'est Albert, enchanté</h1>
      <p class="text-end">
        Je suis un développeur front end basé à Paris et j'aide les entreprises
        dans la création de leurs interfaces utilisateurs.
      </p>
      <p class="text-end">
        Mon objectif est de créer des interface toujours plus intuitives pour
        l'utilisateur final.
      </p>
    </div>
    <div class="mx-16">
      <h1 class="font-bold text-center">Ils parlent de moi (en bien)</h1>
      <div class="bg-gray-400 rounded-md py-4 my-4">
        <h3 class="font-bold ml-5">Ehua - <em>Krypto Valley</em></h3>
        <p class="text-center">
          "À l'écoute et motivé, bonne capacité de communication et de
          proposition. Travail rendu dans les temps. Je recommande vivement ce
          prestataire pour une mission front-end."
        </p>
      </div>
    </div>
  </div>
</template>
