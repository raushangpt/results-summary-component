<script>
  import iconMemory from './assets/icon-memory.svg';
  import iconReaction from './assets/icon-reaction.svg';
  import iconVerbal from './assets/icon-verbal.svg';
  import iconVisual from './assets/icon-visual.svg';
</script>

<main
  class="font-hanken-grotesk grid h-screen w-screen select-none place-items-center bg-gray-200">
  <section
    class="w-full max-w-md grid-cols-2 overflow-hidden rounded-3xl bg-white lg:grid lg:max-w-3xl">
    <div
      class="rounded-3xl bg-gradient-to-t from-blue-900 to-blue-500 p-8 lg:px-14 lg:py-10">
      <h1 class="text-center text-xl font-bold text-white/70">Your Result</h1>
      <div
        class="mx-auto my-10 flex h-32 w-32 flex-col items-center justify-center space-y-2 rounded-full bg-gradient-to-b from-blue-900 to-blue-500 lg:h-48 lg:w-48">
        <h1 class="text-5xl font-extrabold text-white lg:text-6xl">76</h1>
        <span class="text-white/50">of 100</span>
      </div>
      <div class="space-y-4">
        <h1 class="text-center text-2xl font-bold text-white">Great</h1>
        <p class="text-center text-lg text-white/70">
          You scored higher than 65% of the people who have taken these tests.
        </p>
      </div>
    </div>
    <div class="flex flex-col justify-between space-y-8 px-8 py-10">
      <h1 class="text-2xl font-bold text-black">Summary</h1>

      <div class="space-y-4">
        <div
          class="flex items-center justify-between rounded-md bg-red-100 p-4">
          <div class="flex items-center gap-x-4">
            <img src={iconReaction} alt="" />
            <span class="font-bold text-red-500">Reaction</span>
          </div>
          <div>
            <span class="font-bold text-black">80</span>
            <span class="text-gray-400">/ 100</span>
          </div>
        </div>

        <div
          class="flex items-center justify-between rounded-md bg-yellow-100 p-4">
          <div class="flex items-center gap-x-4">
            <img src={iconMemory} alt="" />
            <span class="font-bold text-red-500">Memory</span>
          </div>
          <div>
            <span class="font-bold text-black">92</span>
            <span class="text-gray-400">/ 100</span>
          </div>
        </div>

        <div
          class="flex items-center justify-between rounded-md bg-green-100 p-4">
          <div class="flex items-center gap-x-4">
            <img src={iconVerbal} alt="" />
            <span class="font-bold text-red-500">Verbal</span>
          </div>
          <div>
            <span class="font-bold text-black">61</span>
            <span class="text-gray-400">/ 100</span>
          </div>
        </div>

        <div
          class="flex items-center justify-between rounded-md bg-blue-100 p-4">
          <div class="flex items-center gap-x-4">
            <img src={iconVisual} alt="" />
            <span class="font-bold text-red-500">Visual</span>
          </div>
          <div>
            <span class="font-bold text-black">72</span>
            <span class="text-gray-400">/ 100</span>
          </div>
        </div>
      </div>

      <button
        class="rounded-full bg-gray-700 py-3 text-white transition-all hover:bg-blue-700 active:scale-95"
        >Continue</button>
    </div>
  </section>
</main>
