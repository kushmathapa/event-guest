<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">This app was created using : Nuxt.js, Vue 2, over postgres (V 14.1)</h1>
      <h2 class="subtitle text-center">
        As a part of Web technology assignment, assigned by Nawaraj Paudel. Coded by Kushma Thapa, Masters in
        E-governance (76241008)
      </h2>
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">
        Submit a guest entry
        <a class="underline" href="/guest">here</a>
      </h3>

      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">
        View the list of all guests
        <a class="underline" href="/guestList">here</a>
      </h3>

      <GuestList />
    </section>
  </main>
</template>