<template>
  <div class="sm:flex flex-col flex-grow">
    <div class="sm:flex flex-col flex-grow justify-center items-center container mx-auto w-full h-full p-4 sm:px-0 sm:py-8">
      <!-- BEFORE 🔥 DESIGN TIPS -->
      <aside class="block text-red text-sm text-center font-bold uppercase mb-4 -- animated fadeIn fast delay-1s">
        Same color icons and text
      </aside>
      <section class="bg-white border-teal border-t-4 shadow w-full mb-12">
        <nav class="border-b text-sm">
          <div class="flex justify-center container mx-auto">
            <a class="flex items-center bg-white hover:bg-grey-lightest border-white hover:border-grey-lightest border-b-2 text-grey-darkest hover:text-black no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M12 2c5.514 0 10 4.486 10 10s-4.486 10-10 10-10-4.486-10-10 4.486-10 10-10zm0-2c-6.617 0-12 5.383-12 12s5.383 12 12 12 12-5.383 12-12-5.383-12-12-12zm8.021 9.593c-.141-.427-.314-.844-.516-1.242l-2.454 1.106c.217.393.39.81.517 1.242l2.453-1.106zm-12.573-.904c.271-.354.58-.674.919-.957l-1.89-1.968c-.328.294-.637.615-.918.957l1.889 1.968zm1.715-1.514c.379-.221.781-.396 1.198-.523l-1.034-2.569c-.41.142-.812.318-1.198.524l1.034 2.568zm-2.759 3.616c.121-.435.288-.854.498-1.25l-2.47-1.067c-.197.403-.364.823-.498 1.25l2.47 1.067zm9.434-6.2c-.387-.205-.79-.379-1.2-.519l-1.024 2.573c.417.125.82.299 1.2.519l1.024-2.573zm2.601 2.13c-.282-.342-.59-.664-.918-.957l-1.89 1.968c.339.283.647.604.918.957l1.89-1.968zm-5.791-3.059c-.219-.017-.437-.026-.649-.026s-.431.009-.65.026v2.784c.216-.025.434-.038.65-.038.216 0 .434.013.649.038v-2.784zm-.648 13.782c-1.294 0-2.343-1.049-2.343-2.343 0-.883.489-1.652 1.21-2.051l1.133-5.31 1.133 5.309c.722.399 1.21 1.168 1.21 2.051 0 1.295-1.049 2.344-2.343 2.344z">
                </path>
              </svg>
              <b class="ml-2">Dashboard</b>
            </a>
            <a class="flex items-center bg-white border-teal hover:border-teal-dark border-b-2 text-grey-darkest hover:text-black no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current text-teal-dark w-6 h-6" xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24">
                <path
                  d="M9.776 2l11.395 11.395-7.78 7.777-11.391-11.391v-7.781h7.776zm.829-2h-10.605v10.609l13.391 13.391 10.609-10.604-13.395-13.396zm-3.191 7.414c-.781.782-2.046.782-2.829.001-.781-.783-.781-2.048 0-2.829.782-.782 2.048-.781 2.829-.001.782.783.781 2.047 0 2.829z">
                </path>
              </svg>
              <b class="ml-2">Products</b>
            </a>
            <a class="flex items-center bg-white hover:bg-grey-lightest border-white hover:border-grey-lightest border-b-2 text-grey-darkest hover:text-black no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M20.822 18.096c-3.439-.794-6.641-1.49-5.09-4.418 4.719-8.912 1.251-13.678-3.732-13.678-5.082 0-8.465 4.949-3.732 13.678 1.598 2.945-1.725 3.641-5.09 4.418-2.979.688-3.178 2.143-3.178 4.663l.005 1.241h1.995c0-3.134-.125-3.55 1.838-4.003 2.851-.657 5.543-1.278 6.525-3.456.359-.795.592-2.103-.338-3.815-2.058-3.799-2.578-7.089-1.423-9.026 1.354-2.275 5.426-2.264 6.767-.034 1.15 1.911.639 5.219-1.403 9.076-.91 1.719-.671 3.023-.31 3.814.99 2.167 3.707 2.794 6.584 3.458 1.879.436 1.76.882 1.76 3.986h1.995l.005-1.241c0-2.52-.199-3.975-3.178-4.663z">
                </path>
              </svg>
              <b class="ml-2">Customers</b>
            </a>
            <a class="flex items-center bg-white hover:bg-grey-lightest border-white hover:border-grey-lightest border-b-2 text-grey-darkest hover:text-black no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M2 17h-2v-4h2v4zm3 7v-2h-3v-3h-2v5h5zm6-2h-4v2h4v-2zm-11-11h2v-3h3v-2h-5v5zm24 .044c0 1.64-1.352 2.956-3.146 2.956-.533 0-1.083-.119-1.605-.373-1.511-.731-2.296-2.333-1.943-3.774.203-.822-.23-.934-.891-1.253l-11.036-5.341s1.322-1.812 2.76-1.117c.881.427 4.424 2.136 7.477 3.617l.766-.368c.662-.319 1.094-.43.895-1.252-.351-1.442.439-3.043 1.952-3.77.52-.251 1.067-.369 1.595-.369 1.799 0 3.147 1.32 3.147 2.956 0 1.23-.766 2.454-2.032 3.091-1.266.634-2.15.14-3.406.75l-.394.19.431.21c1.254.614 2.142.122 3.404.759 1.262.638 2.026 1.861 2.026 3.088zm-5.133-7.011c.381.795 1.459 1.072 2.406.617.945-.455 1.405-1.472 1.027-2.267-.381-.796-1.46-1.073-2.406-.618-.946.455-1.408 1.472-1.027 2.268zm-2.834 2.819c0-.322-.261-.583-.583-.583-.321 0-.583.261-.583.583s.262.583.583.583c.322.001.583-.261.583-.583zm5.272 2.499c-.945-.457-2.025-.183-2.408.611-.381.795.078 1.814 1.022 2.271.945.458 2.024.184 2.406-.611.382-.795-.075-1.814-1.02-2.271zm-6.305 12.649h-2v2h4v-5h-2v3zm.861-9h-.861v4h2v-2.51c-.471-.432-.847-.942-1.139-1.49zm-10.528-2.297s1.317 1.815 2.755 1.124l6.598-3.181-2.539-1.229-6.814 3.286z">
                </path>
              </svg>
              <b class="ml-2">Discounts</b>
            </a>
          </div>
        </nav>
        <div class="flex justify-end container mx-auto p-3">
          <button
            class="bg-transparent text-teal-dark focus:text-teal-darker focus:underline text-sm font-bold ml-3 px-6 py-3 focus:outline-none"
            type="button">
            Cancel
          </button>
          <button
            class="bg-teal hover:bg-teal-dark focus:bg-teal-dark text-white text-sm font-bold rounded ml-3 px-6 py-3 focus:shadow-outline focus:outline-none"
            type="button">
            Preview
          </button>
        </div>
      </section>

      <!-- AFTER 🔥 DESIGN TIPS
      -->
      <aside class="block text-red text-sm text-center font-bold uppercase mb-4 -- animated fadeIn fast delay-2s">
        Icons slightly lighter than text
      </aside>
      <section class="bg-white border-teal border-t-4 shadow w-full mb-12">
        <nav class="border-b text-sm">
          <div class="flex justify-center container mx-auto">
            <a class="flex items-center bg-white hover:bg-grey-lightest border-white hover:border-grey-lightest border-b-2 text-grey-dark hover:text-grey-darker no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M12 2c5.514 0 10 4.486 10 10s-4.486 10-10 10-10-4.486-10-10 4.486-10 10-10zm0-2c-6.617 0-12 5.383-12 12s5.383 12 12 12 12-5.383 12-12-5.383-12-12-12zm8.021 9.593c-.141-.427-.314-.844-.516-1.242l-2.454 1.106c.217.393.39.81.517 1.242l2.453-1.106zm-12.573-.904c.271-.354.58-.674.919-.957l-1.89-1.968c-.328.294-.637.615-.918.957l1.889 1.968zm1.715-1.514c.379-.221.781-.396 1.198-.523l-1.034-2.569c-.41.142-.812.318-1.198.524l1.034 2.568zm-2.759 3.616c.121-.435.288-.854.498-1.25l-2.47-1.067c-.197.403-.364.823-.498 1.25l2.47 1.067zm9.434-6.2c-.387-.205-.79-.379-1.2-.519l-1.024 2.573c.417.125.82.299 1.2.519l1.024-2.573zm2.601 2.13c-.282-.342-.59-.664-.918-.957l-1.89 1.968c.339.283.647.604.918.957l1.89-1.968zm-5.791-3.059c-.219-.017-.437-.026-.649-.026s-.431.009-.65.026v2.784c.216-.025.434-.038.65-.038.216 0 .434.013.649.038v-2.784zm-.648 13.782c-1.294 0-2.343-1.049-2.343-2.343 0-.883.489-1.652 1.21-2.051l1.133-5.31 1.133 5.309c.722.399 1.21 1.168 1.21 2.051 0 1.295-1.049 2.344-2.343 2.344z">
                </path>
              </svg>
              <b class="ml-2">Dashboard</b>
            </a>
            <a class="flex items-center bg-white border-teal hover:border-teal-dark border-b-2 text-grey-darkest hover:text-black no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current text-teal-dark w-6 h-6" xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24">
                <path
                  d="M9.776 2l11.395 11.395-7.78 7.777-11.391-11.391v-7.781h7.776zm.829-2h-10.605v10.609l13.391 13.391 10.609-10.604-13.395-13.396zm-3.191 7.414c-.781.782-2.046.782-2.829.001-.781-.783-.781-2.048 0-2.829.782-.782 2.048-.781 2.829-.001.782.783.781 2.047 0 2.829z">
                </path>
              </svg>
              <b class="ml-2">Products</b>
            </a>
            <a class="flex items-center bg-white hover:bg-grey-lightest border-white hover:border-grey-lightest border-b-2 text-grey-dark hover:text-grey-darker no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M20.822 18.096c-3.439-.794-6.641-1.49-5.09-4.418 4.719-8.912 1.251-13.678-3.732-13.678-5.082 0-8.465 4.949-3.732 13.678 1.598 2.945-1.725 3.641-5.09 4.418-2.979.688-3.178 2.143-3.178 4.663l.005 1.241h1.995c0-3.134-.125-3.55 1.838-4.003 2.851-.657 5.543-1.278 6.525-3.456.359-.795.592-2.103-.338-3.815-2.058-3.799-2.578-7.089-1.423-9.026 1.354-2.275 5.426-2.264 6.767-.034 1.15 1.911.639 5.219-1.403 9.076-.91 1.719-.671 3.023-.31 3.814.99 2.167 3.707 2.794 6.584 3.458 1.879.436 1.76.882 1.76 3.986h1.995l.005-1.241c0-2.52-.199-3.975-3.178-4.663z">
                </path>
              </svg>
              <b class="ml-2">Customers</b>
            </a>
            <a class="flex items-center bg-white hover:bg-grey-lightest border-white hover:border-grey-lightest border-b-2 text-grey-dark hover:text-grey-darker no-underline mx-4 px-2 py-4"
              href="#">
              <svg class="block fill-current w-6 h-6" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                <path
                  d="M2 17h-2v-4h2v4zm3 7v-2h-3v-3h-2v5h5zm6-2h-4v2h4v-2zm-11-11h2v-3h3v-2h-5v5zm24 .044c0 1.64-1.352 2.956-3.146 2.956-.533 0-1.083-.119-1.605-.373-1.511-.731-2.296-2.333-1.943-3.774.203-.822-.23-.934-.891-1.253l-11.036-5.341s1.322-1.812 2.76-1.117c.881.427 4.424 2.136 7.477 3.617l.766-.368c.662-.319 1.094-.43.895-1.252-.351-1.442.439-3.043 1.952-3.77.52-.251 1.067-.369 1.595-.369 1.799 0 3.147 1.32 3.147 2.956 0 1.23-.766 2.454-2.032 3.091-1.266.634-2.15.14-3.406.75l-.394.19.431.21c1.254.614 2.142.122 3.404.759 1.262.638 2.026 1.861 2.026 3.088zm-5.133-7.011c.381.795 1.459 1.072 2.406.617.945-.455 1.405-1.472 1.027-2.267-.381-.796-1.46-1.073-2.406-.618-.946.455-1.408 1.472-1.027 2.268zm-2.834 2.819c0-.322-.261-.583-.583-.583-.321 0-.583.261-.583.583s.262.583.583.583c.322.001.583-.261.583-.583zm5.272 2.499c-.945-.457-2.025-.183-2.408.611-.381.795.078 1.814 1.022 2.271.945.458 2.024.184 2.406-.611.382-.795-.075-1.814-1.02-2.271zm-6.305 12.649h-2v2h4v-5h-2v3zm.861-9h-.861v4h2v-2.51c-.471-.432-.847-.942-1.139-1.49zm-10.528-2.297s1.317 1.815 2.755 1.124l6.598-3.181-2.539-1.229-6.814 3.286z">
                </path>
              </svg>
              <b class="ml-2">Discounts</b>
            </a>
          </div>
        </nav>
        <div class="flex justify-end container mx-auto p-3">
          <button
            class="bg-transparent text-teal-dark focus:text-teal-darker focus:underline text-sm font-bold ml-3 px-6 py-3 focus:outline-none"
            type="button">
            Cancel
          </button>
          <button
            class="bg-teal hover:bg-teal-dark focus:bg-teal-dark text-white text-sm font-bold rounded ml-3 px-6 py-3 focus:shadow-outline focus:outline-none"
            type="button">
            Preview
          </button>
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
          text: 'If I am using icons that have more weight than the text, I typically make the icons slightly lighter than the text for inactive states.',
          owner: 'Steve Schoger',
          dateText: '8 Jun 2017',
          links: 'https://twitter.com/steveschoger/status/872865304719892480',
        }
      }
    }
  }
</script>
