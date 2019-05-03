<template>
  <div>
    <div class="w-screen h-screen">
      <hr class="bg-indigo-dark bg-repeat w-full h-6 m-0"
        style="background-image:url(https://res.cloudinary.com/caneco/image/upload/v1556202367/caneco.xyz/design-tips/pattern-purple_ben82l.svg)">
      <header class="container leading-tight mx-auto mt-6 mb-8 md:my-12 px-4 md:px-0">
        <h1 class="text-indigo-darker text-xl md:text-3xl font-medium">The “🔥 <b>Design Tips</b>” series, now in
          TailwindCSS</h1>
        <h2 class="text-indigo-light text-xs md:text-sm font-normal mt-2 md:mt-0">Tailored by <a
            href="http://twitter.com/caneco"
            class="text-indigo-dark no-underline hover:text-indigo-darker hover:underline">@caneco</a>, inspired by <a
            href="http://twitter.com/steveschoger"
            class="text-indigo-dark no-underline hover:text-indigo-darker hover:underline">@steveschoger</a> && <a
            href="http://twitter.com/adamwathan"
            class="text-indigo-dark no-underline hover:text-indigo-darker hover:underline">@adamwathan</a></h2>
      </header>
      <section class="flex-grow container mx-auto">
        <div class="flex flex-wrap items-stretch md:-mx-4">
          <article class="w-full sm:w-1/2 md:w-1/3 mb-8 px-4"
            v-for="tips in designs" v-key="tips.url">
            <div class="bg-white shadow rounded h-full">
              <a :href="tips.url"><img
                  class="block rounded-t min-w-full h-auto mx-auto shadow-inner"
                  :src="tips.thumbnail_url"
                  alt=""></a>
              <p class="text-grey-darker text-sm leading-tight p-4">{{ tips.title }}</p>
            </div>
          </article>
        </div>
      </section>
    </div>
    <a class="absolute pin-t pin-r focus:outline-none" href="https://github.com/caneco/design-tips" target="_blank"
      tabindex="-1">
      <svg class="block w-16 sm:w-24 h-16 sm:h-24" viewBox="0 0 250 250">
        <path class="fill-current text-black" d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path>
        <path class="fill-current text-white"
          d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2">
        </path>
        <path class="fill-current text-white"
          d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z">
        </path>
      </svg>
    </a>
  </div>
</template>

<script>
  import designs from '@/pages/designs.json'
  export default {
    data() {
      return {
        designs: designs
      }
    }
  }
</script>
