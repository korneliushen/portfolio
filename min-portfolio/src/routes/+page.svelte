<script>
  import BxsSchool from '~icons/bxs/school';
  import MaterialSymbolsLocationOn from '~icons/material-symbols/location-on';
</script>


<main class="w-screen flex">
    <section class="  h-[70em] w-3/12">
        <div></div>
    </section>
    <section class="w-5/12 h-[70em]  flex flex-col justify-center space-y-10 text-text">
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
          <p class="text-2xl">Elvebakken</p>
        </div>
      </div>
      <div class="space-x-4">
        <button class="w-32 h-12 bg-secondary rounded-lg text-lg">Prosjekter</button>
        <button class="w-32 h-12 border-accent border-[1px] rounded-lg text-lg">Om meg</button>
      </div>
    </section>
</main>




<style lang="postcss">
    :global(html) {
      background-color: theme('colors.background');
    }
</style>


