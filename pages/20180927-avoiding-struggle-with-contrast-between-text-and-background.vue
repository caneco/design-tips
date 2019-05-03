<template>
  <div class="sm:flex flex-col flex-grow">
    <div class="sm:flex flex-col flex-grow justify-center items-center container mx-auto w-full h-full p-4 sm:px-0 sm:py-8">
      <!-- BEFORE 🔥 DESIGN TIPS -->
      <section class="w-full flex -mx-2 sm:mb-24">
        <svg class="flex-none fill-current bg-white text-red rounded-full w-8 h-8 ml-2 mr-4"
          xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path
            d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm4.151 17.943l-4.143-4.102-4.117 4.159-1.833-1.833 4.104-4.157-4.162-4.119 1.833-1.833 4.155 4.102 4.106-4.16 1.849 1.849-4.1 4.141 4.157 4.104-1.849 1.849z">
          </path>
        </svg>
        <div class="bg-white rounded-lg shadow w-full mx-2 relative">
          <div class="p-4">
            <div class="flex justify-between items-center mb-1">
              <p class="text-sm font-medium">Carl Phillips</p>
              <span
                class="bg-orange text-orange-lightest text-xs font-medium rounded-full px-3 py-1 float-right">Pending</span>
            </div>
            <p class="text-blue-dark text-xl mb-1">US$249.00</p>
            <small class="text-grey-dark text-xs">2 days ago</small>
          </div>
          <button
            class="flex justify-center items-center block bg-grey-lighter hover:bg-grey-light text-grey-darkest text-sm rounded-b-lg w-full p-3 focus:outline-none">
            View Invoice ›
          </button>
          <aside class="absolute pin-t pin-r -mt-12 -- animated fadeIn fast delay-1s">
            <span>2.04 (<b>Fail</b>)</span>
            <div class="border-red border-l-2 h-12 absolute pin-t pin-l mt-5 ml-2"></div>
          </aside>
        </div>
        <div class="bg-white rounded-lg shadow w-full mx-2 relative">
          <div class="p-4">
            <div class="flex justify-between items-center mb-1">
              <p class="text-sm font-medium">Tyler Burns</p>
              <span
                class="bg-red text-red-lightest text-xs font-medium rounded-full px-3 py-1 float-right">Pending</span>
            </div>
            <p class="text-blue-dark text-xl mb-1">US$479.00</p>
            <small class="text-grey-dark text-xs">8 days ago</small>
          </div>
          <button
            class="flex justify-center items-center block bg-grey-lighter hover:bg-grey-light text-grey-darkest text-sm rounded-b-lg w-full p-3 focus:outline-none">
            View Invoice ›
          </button>
          <aside class="absolute pin-t pin-r -mt-12 -mr-6 -- animated fadeIn fast delay-1s">
            <span>3.80 (<b>AA<small>18pt</small></b>)</span>
            <div class="border-red border-l-2 h-12 absolute pin-t pin-l mt-5 ml-2"></div>
          </aside>
        </div>
        <div class="bg-white rounded-lg shadow w-full mx-2 relative">
          <div class="p-4">
            <div class="flex justify-between items-center mb-1">
              <p class="text-sm font-medium">Brenda Jenkins</p>
              <span
                class="bg-green text-green-lightest text-xs font-medium rounded-full px-3 py-1 float-right">Pending</span>
            </div>
            <p class="text-blue-dark text-xl mb-1">US$329.00</p>
            <small class="text-grey-dark text-xs">9 days ago</small>
          </div>
          <button
            class="flex justify-center items-center block bg-grey-lighter hover:bg-grey-light text-grey-darkest text-sm rounded-b-lg w-full p-3 focus:outline-none">
            View Invoice ›
          </button>
          <aside class="absolute pin-t pin-r -mt-12 -- animated fadeIn fast delay-1s">
            <span>2.15 (<b>Fail</b>)</span>
            <div class="border-red border-l-2 h-12 absolute pin-t pin-l mt-5 ml-2"></div>
          </aside>
        </div>
      </section>

      <!-- AFTER 🔥 DESIGN TIPS -->
      <section class="w-full flex -mx-2">
        <svg class="flex-none fill-current bg-white text-green rounded-full w-8 h-8 ml-2 mr-4"
          xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
          <path
            d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-1.25 17.292l-4.5-4.364 1.857-1.858 2.643 2.506 5.643-5.784 1.857 1.857-7.5 7.643z">
          </path>
        </svg>
        <div class="bg-white rounded-lg shadow w-full mx-2 relative">
          <div class="p-4">
            <div class="flex justify-between items-center mb-1">
              <p class="text-sm font-medium">Carl Phillips</p>
              <span
                class="bg-orange-lighter text-orange-darkest text-xs font-medium rounded-full px-3 py-1 float-right">Pending</span>
            </div>
            <p class="text-blue-dark text-xl mb-1">US$249.00</p>
            <small class="text-grey-dark text-xs">2 days ago</small>
          </div>
          <button
            class="flex justify-center items-center block bg-grey-lighter hover:bg-grey-light text-grey-darkest text-sm rounded-b-lg w-full p-3 focus:outline-none">
            View Invoice ›
          </button>
          <aside class="absolute pin-t pin-r -mt-12 -mr-2 -- animated fadeIn fast delay-2s">
            <span>9.82 (<b>AAA</b>)</span>
            <div class="border-red border-l-2 h-12 absolute pin-t pin-l mt-5 ml-2"></div>
          </aside>
        </div>
        <div class="bg-white rounded-lg shadow w-full mx-2 relative">
          <div class="p-4">
            <div class="flex justify-between items-center mb-1">
              <p class="text-sm font-medium">Tyler Burns</p>
              <span
                class="bg-red-lighter text-red-darkest text-xs font-medium rounded-full px-3 py-1 float-right">Pending</span>
            </div>
            <p class="text-blue-dark text-xl mb-1">US$479.00</p>
            <small class="text-grey-dark text-xs">8 days ago</small>
          </div>
          <button
            class="flex justify-center items-center block bg-grey-lighter hover:bg-grey-light text-grey-darkest text-sm rounded-b-lg w-full p-3 focus:outline-none">
            View Invoice ›
          </button>
          <aside class="absolute pin-t pin-r -mt-12 -mr-2 -- animated fadeIn fast delay-2s">
            <span>9.22 (<b>AAA</b>)</span>
            <div class="border-red border-l-2 h-12 absolute pin-t pin-l mt-5 ml-2"></div>
          </aside>
        </div>
        <div class="bg-white rounded-lg shadow w-full mx-2 relative">
          <div class="p-4">
            <div class="flex justify-between items-center mb-1">
              <p class="text-sm font-medium">Brenda Jenkins</p>
              <span
                class="bg-green-lighter text-green-darkest text-xs font-medium rounded-full px-3 py-1 float-right">Pending</span>
            </div>
            <p class="text-blue-dark text-xl mb-1">US$329.00</p>
            <small class="text-grey-dark text-xs">9 days ago</small>
          </div>
          <button
            class="flex justify-center items-center block bg-grey-lighter hover:bg-grey-light text-grey-darkest text-sm rounded-b-lg w-full p-3 focus:outline-none">
            View Invoice ›
          </button>
          <aside class="absolute pin-t pin-r -mt-12 -mr-2 -- animated fadeIn fast delay-2s">
            <span>11.28 (<b>AAA</b>)</span>
            <div class="border-red border-l-2 h-12 absolute pin-t pin-l mt-5 ml-2"></div>
          </aside>
        </div>
      </section>
    </div>
    <Tweet :tweet="tweet"></Tweet>
  </div>
</template>

<script>
  import Tweet from '@/components/Tweet'

  export default {
    layout: 'showcase',
    components: {
      Tweet
    },
    data() {
      return {
        tweet: {
          text: 'Achieving an accessible contrast ratio is very difficult when using white text on a colored background. Using dark colored text on a soft colored background is much easier to make accessible, and usually looks better to boot.',
          owner: 'Steve Schoger',
          dateText: '27 Sep 2018',
          links: 'https://twitter.com/steveschoger/status/1045371124274483200',
        }
      }
    }
  }
</script>
