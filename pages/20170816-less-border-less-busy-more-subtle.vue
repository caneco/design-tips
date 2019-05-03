<template>
  <div class="sm:flex flex-col flex-grow">
    <div
      class="sm:flex flex-grow justify-center items-center container mx-auto w-full h-full p-4 sm:px-0 sm:py-8">
      <!-- BEFORE 🔥 DESIGN TIPS -->
      <section class="w-full sm:w-1/2 md:w-1/3 sm:mx-4 mb-4">
        <svg class="block fill-current bg-white text-red rounded-full w-8 h-8 mb-4" xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24">
          <path
            d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm4.151 17.943l-4.143-4.102-4.117 4.159-1.833-1.833 4.104-4.157-4.162-4.119 1.833-1.833 4.155 4.102 4.106-4.16 1.849 1.849-4.1 4.141 4.157 4.104-1.849 1.849z">
          </path>
        </svg>
        <div class="bg-white rounded-lg border-grey border">
          <div class="text-grey-darkest text-lg leading-none leading-none font-medium px-5 py-4">
            Contacts
          </div>
          <div class="px-3_">
            <div class="bg-grey-lighter border-grey border-t border-b p-2">
              <div class="flex items-center bg-white border border-grey rounded w-full px-2">
                <svg class="block fill-current text-grey w-5 h-5" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <path
                    d="M23.809 21.646l-6.205-6.205c1.167-1.605 1.857-3.579 1.857-5.711 0-5.365-4.365-9.73-9.731-9.73-5.365 0-9.73 4.365-9.73 9.73 0 5.366 4.365 9.73 9.73 9.73 2.034 0 3.923-.627 5.487-1.698l6.238 6.238 2.354-2.354zm-20.955-11.916c0-3.792 3.085-6.877 6.877-6.877s6.877 3.085 6.877 6.877-3.085 6.877-6.877 6.877c-3.793 0-6.877-3.085-6.877-6.877z">
                  </path>
                </svg>
                <input class="self-stretch bg-transparent text-sm w-full px-2 py-3 focus:outline-none" type="text"
                  placeholder="Search teams of members">
              </div>
            </div>
            <ul class="list-reset text-grey-darkest text-sm font-medium">
              <li class="flex justify-between items-center bg-white border-grey border-b px-4 py-2">
                <svg class="block fill-current text-grey w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Tighten Co.
                </span>
                <span class="text-grey-dark text-xs">
                  Team
                </span>
              </li>
              <li class="flex justify-between items-center bg-blue-lightest border-grey border-b px-4 py-2">
                <svg class="block fill-current text-green w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow text-blue-dark mx-3">
                  Taylor Otwell
                </span>
                <span class="text-grey-dark text-xs">
                  Member
                </span>
              </li>
              <li class="flex justify-between items-center bg-white border-grey border-b px-4 py-2">
                <svg class="block fill-current text-grey w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Adam Wathan
                </span>
                <span class="text-grey-dark text-xs">
                  Member
                </span>
              </li>
              <li class="flex justify-between items-center bg-white border-grey border-b px-4 py-2">
                <svg class="block fill-current text-grey w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Duke Street Studio Inc.
                </span>
                <span class="text-grey-dark text-xs">
                  Team
                </span>
              </li>
              <li class="flex justify-between items-center bg-white border-grey border-b px-4 py-2">
                <svg class="block fill-current text-green w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Jeffrey Way
                </span>
                <span class="text-grey-dark text-xs">
                  Member
                </span>
              </li>
            </ul>
          </div>
          <div class="flex justify-end items-center bg-grey-lighter rounded-b-lg p-3">
            <button
              class="bg-transparent text-grey-dark focus:text-grey-darker focus:underline text-sm font-bold px-5 py-2 focus:outline-none"
              type="button">
              Cancel
            </button>
            <button
              class="bg-blue hover:bg-blue-dark focus:bg-blue-dark text-white text-sm rounded px-5 py-2 focus:shadow-outline focus:outline-none"
              type="button">
              Invite
            </button>
          </div>
        </div>
      </section>

      <!-- AFTER 🔥 DESIGN TIPS -->
      <section class="w-full sm:w-1/2 md:w-1/3 sm:mx-4 mb-4 relative">
        <svg class="block fill-current bg-white text-green rounded-full w-8 h-8 mb-4" xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24">
          <path
            d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-1.25 17.292l-4.5-4.364 1.857-1.858 2.643 2.506 5.643-5.784 1.857 1.857-7.5 7.643z">
          </path>
        </svg>
        <div class="bg-white rounded-lg shadow">
          <div class="text-grey-darkest text-lg leading-none font-medium px-5 py-4">
            Contacts
          </div>
          <div class="px-3">
            <div class="flex items-center bg-grey-lighter rounded w-full px-2">
              <svg class="block fill-current text-grey w-5 h-5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M23.809 21.646l-6.205-6.205c1.167-1.605 1.857-3.579 1.857-5.711 0-5.365-4.365-9.73-9.731-9.73-5.365 0-9.73 4.365-9.73 9.73 0 5.366 4.365 9.73 9.73 9.73 2.034 0 3.923-.627 5.487-1.698l6.238 6.238 2.354-2.354zm-20.955-11.916c0-3.792 3.085-6.877 6.877-6.877s6.877 3.085 6.877 6.877-3.085 6.877-6.877 6.877c-3.793 0-6.877-3.085-6.877-6.877z">
                </path>
              </svg>
              <input class="self-stretch bg-transparent text-sm w-full px-2 py-3 focus:outline-none" type="text"
                placeholder="Search teams of members">
            </div>
            <ul class="list-reset text-grey-darkest text-sm font-medium my-1">
              <li class="flex justify-between items-center bg-white rounded p-3">
                <svg class="block fill-current text-grey w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Tighten Co.
                </span>
                <span class="text-grey-dark text-xs">
                  Team
                </span>
              </li>
              <li class="flex justify-between items-center bg-blue-lightest rounded p-3">
                <svg class="block fill-current text-green w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow text-blue-dark mx-3">
                  Taylor Otwell
                </span>
                <span class="text-grey-dark text-xs">
                  Member
                </span>
              </li>
              <li class="flex justify-between items-center bg-white rounded p-3">
                <svg class="block fill-current text-grey w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Adam Wathan
                </span>
                <span class="text-grey-dark text-xs">
                  Member
                </span>
              </li>
              <li class="flex justify-between items-center bg-white rounded p-3">
                <svg class="block fill-current text-grey w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Duke Street Studio Inc.
                </span>
                <span class="text-grey-dark text-xs">
                  Team
                </span>
              </li>
              <li class="flex justify-between items-center bg-white rounded p-3">
                <svg class="block fill-current text-green w-2 h-2" xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24">
                  <circle cx="12" cy="12" r="12" />
                </svg>
                <span class="flex-grow mx-3">
                  Jeffrey Way
                </span>
                <span class="text-grey-dark text-xs">
                  Member
                </span>
              </li>
            </ul>
          </div>
          <div class="flex justify-end items-center bg-grey-lighter rounded-b-lg mt-3 p-3">
            <button
              class="bg-transparent text-grey-dark focus:text-grey-darker focus:underline text-sm font-bold px-5 py-2 focus:outline-none"
              type="button">
              Cancel
            </button>
            <button
              class="bg-blue hover:bg-blue-dark focus:bg-blue-dark text-white text-sm rounded px-5 py-2 focus:shadow-outline focus:outline-none"
              type="button">
              Invite
            </button>
          </div>
        </div>

        <aside class="flex text-red text-sm absolute pin-t pin-r -- animated fadeIn fast delay-1s"
          style="margin-right:-240px;margin-top:100px;">
          <div class="border-red border-t-2 w-10 h-px mt-2 mr-3"></div>
          <span>
            <b>Give search field a background <br>color instead of borders</b>
            <code class="block mt-1">hsl(210, 9%, 96%)</code>
          </span>
        </aside>
        <aside class="flex text-red text-sm absolute pin-t pin-r -- animated fadeIn fast delay-2s"
          style="margin-right:-240px;margin-top:225px;">
          <div class="border-red border-t-2 w-10 h-px mt-2 mr-3"></div>
          <span>
            <b>Replace border with <br>increased space between rows</b>
            <code class="block mt-1">padding: 12px 10px</code>
          </span>
        </aside>
        <aside class="text-red text-sm absolute pin-b pin-l -- animated fadeIn fast delay-1s"
          style="margin-bottom:-80px;">
          <div class="border-red border-l-2 h-10 w-px ml-6 mb-3"></div>
          <span>
            <b>Replace border with <br>increased space between rows</b>
            <code class="block mt-1">padding: 12px 10px</code>
          </span>
        </aside>
        <aside class="text-red text-sm absolute pin-b pin-r -- animated fadeIn fast delay-2s"
          style="margin-right:-240px;margin-bottom:-80px;z-index:-1">
          <div class="border-red border-l-2 h-10 w-px ml-6 mb-3"></div>
          <span>
            <b>Give modal a subtle offset box-shadow <br>instead of borders</b>
            <code class="block mt-1">box-shadow: 0 2px 6px 0 hsla(0, 0%, 0%, 0.2)</code>
          </span>
        </aside>
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
          text: 'Too many borders can make a design look really busy. Here\'s a few ideas that are a bit more subtle.',
          owner: 'Steve Schoger',
          dateText: '16 Aug 2017',
          links: 'https://twitter.com/steveschoger/status/897849211110273024',
        }
      }
    }
  }
</script>
