<template>
  <div class="flex flex-col justify-center min-w-screen min-h-screen">
    <hr class="flex-none bg-indigo-dark bg-repeat w-full h-6 m-0"
      style="background-image:url(https://res.cloudinary.com/caneco/image/upload/v1556202367/caneco.xyz/design-tips/pattern-purple_ben82l.svg)">

    <nuxt />

    <footer class="bg-indigo-darkest flex-none text-indigo-lightest text-xs text-center leading-normal w-full p-3 z-10">
      Tailored by <a class="text-indigo-lightest font-bold no-underline hover:underline focus:outline-none"
        href="http://twitter.com/caneco" target="_blank" tabindex="-1">@caneco</a> and
      inspired from the <a class="text-indigo-lightest font-bold no-underline hover:underline focus:outline-none"
        href="https://twitter.com/i/moments/994601867987619840" target="_blank" tabindex="-1">"Design Tips"</a>,
      a series by <a class="text-indigo-lightest font-bold no-underline hover:underline focus:outline-none"
        href="http://twitter.com/steveschoger" target="_blank" tabindex="-1">@steveschoger</a>
      &amp;&amp; <a class="text-indigo-lightest font-bold no-underline hover:underline focus:outline-none"
        href="http://twitter.com/adamwathan" target="_blank" tabindex="-1">@adamwathan</a>
    </footer>
  </div>
</template>

<script>
    import Tweet from '@/components/Tweet'

    export default {
      components: {
        Tweet
      }
    }
  </script>
