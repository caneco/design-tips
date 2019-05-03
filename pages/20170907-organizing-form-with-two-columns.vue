<template>
  <div class="sm:flex flex-col flex-grow">
    <div
      class="sm:flex flex-grow justify-center items-start container mx-auto w-full h-full p-4 sm:px-0 sm:py-8">
      <!-- BEFORE 🔥 DESIGN TIPS -->
      <section class="w-full sm:w-1/2 sm:mx-4 mb-4">
        <svg class="block fill-current bg-white text-red rounded-full w-8 h-8 mb-4" xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24">
          <path
            d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm4.151 17.943l-4.143-4.102-4.117 4.159-1.833-1.833 4.104-4.157-4.162-4.119 1.833-1.833 4.155 4.102 4.106-4.16 1.849 1.849-4.1 4.141 4.157 4.104-1.849 1.849z">
          </path>
        </svg>
        <div class="bg-white border-grey border">
          <div class="border-b text-grey-darkest text-lg leading-none leading-none font-medium p-4">
            Settings
          </div>
          <div class="p-4">
            <form>
              <div class="mb-4">
                <label class="block text-sm w-full mb-1" for="inputFullName">Full Name</label>
                <input
                  class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                  id="inputFullName" type="text">
              </div>
              <div class="mb-4">
                <label class="block text-sm w-full mb-1" for="inputEmail">Email Address</label>
                <input
                  class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                  id="inputEmail" type="text">
              </div>
              <div class="mb-4">
                <label class="block text-sm w-full mb-1" for="inputPhone">Phone Number</label>
                <input
                  class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                  id="inputPhone" type="text">
              </div>
              <div class="flex mb-4 -mx-2">
                <div class="w-1/2 mx-2">
                  <label class="block text-sm w-full mb-1" for="inputPlan">Plan</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputPlan" type="text">
                </div>
                <div class="w-1/2 mx-2">
                  <label class="block text-sm w-full mb-1" for="inputBilling">Billing Interval</label>
                  <label class="relative" for="inputBilling">
                    <select
                      class="appearance-none bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                      id="inputBilling">
                      <option disabled>Choose one option</option>
                      <option selected>Monthly</option>
                      <option>Yearly</option>
                    </select>
                    <svg class="fill-current text-grey-dark absolute pin-r pin-y w-2 h-full mr-2"
                      xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                      <path d="M12 21l-12-18h24z" />
                    </svg>
                  </label>
                </div>
              </div>
              <div class="mb-4">
                <label class="block text-sm w-full mb-1" for="inputAddress">Street Address</label>
                <input
                  class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                  id="inputAddress" type="text">
              </div>
              <div class="flex mb-4 -mx-2">
                <div class="w-1/2 mx-2">
                  <label class="block text-sm w-full mb-1" for="inputCity">City</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputCity" type="text">
                </div>
                <div class="w-1/2 mx-2">
                  <label class="block text-sm w-full mb-1" for="inputState">State / Province</label>
                  <label class="relative" for="inputState">
                    <select
                      class="appearance-none bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                      id="inputBilling">
                      <option disabled>Choose one option</option>
                      <option>Canada</option>
                      <option selected>Portugal</option>
                    </select>
                    <svg class="fill-current text-grey-dark absolute pin-r pin-y w-2 h-full mr-2"
                      xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                      <path d="M12 21l-12-18h24z" />
                    </svg>
                  </label>
                </div>
              </div>
              <div class="flex mb-4 -mx-2">
                <div class="w-1/2 mx-2">
                  <label class="block text-sm w-full mb-1" for="inputOldPassword">Old Password</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputOldPassword" type="text">
                </div>
                <div class="w-1/2 mx-2">
                  <label class="block text-sm w-full mb-1" for="inputNewPassword">New Password</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputNewPassword" type="text">
                </div>
              </div>
            </form>
          </div>
          <div class="flex justify-end items-center border-t p-4">
            <button
              class="bg-transparent text-grey-dark focus:text-grey-darker focus:underline text-sm font-bold px-5 py-2 focus:outline-none"
              type="button">
              Cancel
            </button>
            <button
              class="bg-blue hover:bg-blue-dark focus:bg-blue-dark text-white text-sm rounded px-5 py-2 focus:shadow-outline focus:outline-none"
              type="button">
              Save Changes
            </button>
          </div>
        </div>
      </section>

      <!-- AFTER 🔥 DESIGN TIPS -->
      <section class="w-full sm:w-1/2 sm:mx-4 mb-4 relative">
        <svg class="block fill-current bg-white text-green rounded-full w-8 h-8 mb-4" xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24">
          <path
            d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm-1.25 17.292l-4.5-4.364 1.857-1.858 2.643 2.506 5.643-5.784 1.857 1.857-7.5 7.643z">
          </path>
        </svg>
        <div class="bg-white border-grey border">
          <div class="text-grey-darkest text-lg leading-none leading-none font-medium p-4">
            Settings
          </div>
          <form class="mx-4">
            <div class="flex border-t -mx-4 py-4">
              <legend class="text-sm text-grey-darker w-1/3 mx-4">Acccount</legend>
              <fieldset class="w-2/3 mx-4">
                <div class="mb-4">
                  <label class="block text-sm mb-1 w-3/4" for="inputFullName">Full Name</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-3/4 px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputFullName" type="text">
                </div>
                <div class="mb-4">
                  <label class="block text-sm mb-1 w-3/4" for="inputEmail">Email Address</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-3/4 px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputEmail" type="text">
                </div>
                <div class="mb-4">
                  <label class="block text-sm mb-1 w-1/2" for="inputPhone">Phone Number</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-1/2 px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputPhone" type="text">
                </div>
              </fieldset>
            </div>
            <div class="flex border-t -mx-4 py-4">
              <legend class="text-sm text-grey-darker w-1/3 mx-4">Billing</legend>
              <fieldset class="w-2/3 mx-4">
                <div class="flex mb-4 -mx-2">
                  <div class="w-1/2 mx-2">
                    <label class="block text-sm w-full mb-1" for="inputPlan">Plan</label>
                    <input
                      class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                      id="inputPlan" type="text">
                  </div>
                  <div class="w-1/2 mx-2">
                    <label class="block text-sm w-full mb-1" for="inputState">Billing Interval</label>
                    <label class="relative" for="inputState">
                      <select
                        class="appearance-none bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                        id="inputBilling">
                        <option disabled>Choose one option</option>
                        <option selected>Monthly</option>
                        <option>Yearly</option>
                      </select>
                      <svg class="fill-current text-grey-dark absolute pin-r pin-y w-2 h-full mr-2"
                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M12 21l-12-18h24z" />
                      </svg>
                    </label>
                  </div>
                </div>
              </fieldset>
            </div>
            <div class="flex border-t -mx-4 py-4">
              <legend class="text-sm text-grey-darker w-1/3 mx-4">Business Address</legend>
              <fieldset class="w-2/3 mx-4">
                <div class="mb-4">
                  <label class="block text-sm w-full mb-1" for="inputAddress">Street Address</label>
                  <input
                    class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                    id="inputAddress" type="text">
                </div>
                <div class="flex mb-4 -mx-2">
                  <div class="w-1/2 mx-2">
                    <label class="block text-sm w-full mb-1" for="inputCity">City</label>
                    <input
                      class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                      id="inputCity" type="text">
                  </div>
                  <div class="w-1/2 mx-2">
                    <label class="block text-sm w-full mb-1" for="inputState">State / Province</label>
                    <label class="relative" for="inputState">
                      <select
                        class="appearance-none bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                        id="inputBilling">
                        <option disabled>Choose one option</option>
                        <option>Canada</option>
                        <option selected>Portugal</option>
                      </select>
                      <svg class="fill-current text-grey-dark absolute pin-r pin-y w-2 h-full mr-2"
                        xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M12 21l-12-18h24z" />
                      </svg>
                    </label>
                  </div>
                </div>
              </fieldset>
            </div>
            <div class="flex border-t -mx-4 p-4">
              <legend class="text-sm text-grey-darker w-1/3 mx-4">Change Password <small
                  class="block text-grey text-xs italic mt-1">Must be at least 8 characters and contain at least 1
                  number.</small></legend>
              <fieldset class="w-2/3 mx-4">
                <div class="flex mb-4 -mx-2">
                  <div class="w-1/2 mx-2">
                    <label class="block text-sm w-full mb-1" for="inputOldPassword">Old Password</label>
                    <input
                      class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                      id="inputOldPassword" type="text">
                  </div>
                  <div class="w-1/2 mx-2">
                    <label class="block text-sm w-full mb-1" for="inputNewPassword">New Password</label>
                    <input
                      class="bg-grey-lightest border focus:border-blue rounded-sm w-full px-2 py-1 focus:shadow-outline focus:outline-none"
                      id="inputNewPassword" type="text">
                  </div>
                </div>
              </fieldset>
            </div>
          </form>
          <div class="flex justify-end items-center border-t p-4">
            <button
              class="bg-transparent text-grey-dark focus:text-grey-darker focus:underline text-sm font-bold px-5 py-2 focus:outline-none"
              type="button">
              Cancel
            </button>
            <button
              class="bg-blue hover:bg-blue-dark focus:bg-blue-dark text-white text-sm rounded px-5 py-2 focus:shadow-outline focus:outline-none"
              type="button">
              Save Changes
            </button>
          </div>
        </div>

        <div class="flex text-center -mt-3">
          <aside class="w-1/3 border-2 border-red relative h-8 mx-px -- animated fadeIn fast delay-1s"
            style="border-top:0">
            <div class="absolute pin-x pin-b -mb-2">
              <span class="bg-grey-light px-8">33%</span>
            </div>
          </aside>
          <aside class="w-2/3 border-2 border-red relative h-8 mx-px -- animated fadeIn fast delay-1s"
            style="border-top:0">
            <div class="absolute pin-x pin-b -mb-2">
              <span class="bg-grey-light px-8">66%</span>
            </div>
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
          text: 'This two-column form layout is great for organizing long forms and filling wider screens without using awkward long form fields.',
          owner: 'Steve Schoger',
          dateText: '7 Sep 2017',
          links: 'https://twitter.com/steveschoger/status/905830324139155458',
        }
      }
    }
  }
</script>
