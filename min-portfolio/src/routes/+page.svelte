<script>
  import BxsSchool from "~icons/bxs/school";
  import MaterialSymbolsLocationOn from "~icons/material-symbols/location-on";
</script>

<main
  class=" scroll-smooth w-screen snap-mandatory overflow-x-hidden overflow-y-scroll flex flex-col items-center"
>
  <section
    class="w-5/12 h-screen flex flex-col justify-center space-y-10 text-text"
  >
    <div>
      <h3 class="text-3xl">Hei jeg heter</h3>
      <h1 class="text-9xl">Henrik</h1>
      <h2 class="text-4xl">og jeg utvikler ting på nettet</h2>
    </div>
    <div class="flex flex-col space-y-3">
      <div class="flex items-center space-x-2">
        <MaterialSymbolsLocationOn class="w-9 h-9 text-accent" />
        <p class="text-2xl">Oslo</p>
      </div>
      <div class="flex items-center space-x-2">
        <BxsSchool class="w-9 h-9 text-accent" />
        <p class="text-2xl">Statnett SF</p>
      </div>
    </div>
    <div class="space-x-4">
      <a href="#prosjekter">
        <button class="w-32 h-12 bg-secondary rounded-lg text-lg"
          >Prosjekter</button
        >
      </a>
      <a href="#om-meg">
        <button class="w-32 h-12 border-accent border-[1px] rounded-lg text-lg"
          >Om meg</button
        >
      </a>
    </div>
  </section>
  <section
    id="om-meg"
    class="w-8/12 h-screen flex flex-col items-center justify-center snap-start"
  >
    <div class="w-3/6 h-1/6 flex flex-col space-y-2">
      <h2 class="text-text text-5xl">Om meg</h2>
      <span class="text-text text-xl"
        >Jeg er lærling hos Statnett SF. Jeg liker å løse problemer ved bruk av
        webutvikling og utvikle morsomme og nyttige applikasjoner
      </span>
    </div>
  </section>
  <section
    id="prosjekter"
    class="w-8/12 h-screen flex flex-col space-y-8 items-center justify-center snap-start"
  >
    <h2 class="text-text text-6xl">Mine prosjekter</h2>
    <div class="flex space-x-8 items-start justify-center">
      <a href="https://github.com/korneliushen/handlel.app">
        <div
          class="min-h-80 w-96 border-primary border-2 rounded-3xl flex flex-col space-y-3 p-5 group"
        >
          <h3
            class="text-text text-4xl group-hover:underline group-hover:decoration-accent"
          >
            Handlel.app
          </h3>
          <span class="text-text text-lg">
            Nettside for å sjekke pris på daglivarer
          </span>
          <img
            class="rounded"
            src="https://i.ibb.co/F4DhYRBG/Screenshot-2025-10-30-185224.webp"
            alt="handlelapp-søk"
            border="0"
          />
        </div>
      </a>
      <a href="https://github.com/korneliushen/geoguessr-extension">
        <div
          class="min-h-80 w-96 border-primary border-2 rounded-3xl flex flex-col space-y-3 p-5 group"
        >
          <h3
            class="text-text text-4xl group-hover:underline group-hover:decoration-accent"
          >
            Geoguessr Chrome extension
          </h3>
          <span class="text-text text-lg">
            Chrome extension for å lagre geoguessr games slik at man enklere kan
            være med
          </span>
          <img
            class="rounded"
            src="https://i.ibb.co/kS6cQZq/Screenshot-2024-05-06-at-10-01-47.png"
            alt="Screenshot-2024-05-06-at-10-01-47"
            border="0"
          />
        </div>
      </a>
    </div>
  </section>
</main>

<style lang="postcss">
  :global(html) {
    background-color: theme("colors.background");
  }
</style>
