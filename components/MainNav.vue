<template>
  <!-- eslint-disable -->
  <header class="absolute top-0 w-full mx-auto bg-transparent max-w-screen-2xl">
    <div
      class="flex items-center justify-end px-4 sm:px-6 md:justify-start md:space-x-10"
    >
      <div class="mt-4 md:hidden">
        <button
          @click="mobileMenu = !mobileMenu"
          type="button"
          class="inline-flex items-center justify-center p-2 text-gray-400 bg-white rounded-md hover:text-white hover:bg-gray-100 focus:outline-none"
        >
          <span class="sr-only">Open menu</span>
          <svg
            class="w-6 h-6 text-gray-900"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            aria-hidden="true"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"
            />
          </svg>
        </button>
      </div>
      <div class="hidden md:flex-1 md:flex md:items-center md:justify-between">
        <div>
          <div class="mb-2">
            <h1 class="text-5xl font-bold text-white">
              KTM JUNIOR RACING PROGRAM
            </h1>
          </div>
          <nav class="flex space-x-10">
            <div class="relative">
              <button
                v-on-clickaway="closeProgramOverviewMenu"
                @click="programOverviewMenu = !programOverviewMenu"
                type="button"
                class="inline-flex items-center text-base font-medium text-white uppercase rounded-md group hover:text-ktmPrimary focus:outline-none"
              >
                <span>Program Overview</span>
                <svg
                  class="w-5 h-5 ml-2 text-gray-400 group-hover:text-white"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  />
                </svg>
              </button>

              <transition
                enter-active-class="transition duration-200 ease-out"
                enter-class="translate-y-1 opacity-0"
                enter-to-class="translate-y-0 opacity-100"
                leave-active-class="transition duration-150 ease-in"
                leave-class="translate-y-0 opacity-100"
                leave-to-class="translate-y-1 opacity-0"
              >
                <div
                  v-show="programOverviewMenu"
                  class="absolute w-screen max-w-xs px-2 mt-3 transform -translate-x-1/2 programOverviewMenu sm:px-0"
                >
                  <div
                    class="overflow-hidden shadow-lg ring-1 ring-black ring-opacity-5"
                  >
                    <div
                      class="relative z-20 grid gap-6 px-5 py-6 bg-white sm:gap-8 sm:p-8"
                    >
                      <nuxt-link
                        to="/program-overview/about"
                        class="block p-3 -m-3 rounded-md hover:bg-gray-50"
                      >
                        <h5 class="text-base font-medium text-gray-900">
                          About
                        </h5>
                        <p class="mt-1 text-sm text-gray-500">
                          Learn about the history of the KTM Junior Program
                        </p>
                      </nuxt-link>

                      <nuxt-link
                        to="/faq"
                        class="block p-3 -m-3 rounded-md hover:bg-gray-50"
                      >
                        <h5 class="text-base font-medium text-gray-900">
                          FAQ
                        </h5>
                        <p class="mt-1 text-sm text-gray-500">
                          Frequently asked questions about the KTM Junior Racing
                          Program
                        </p>
                      </nuxt-link>

                      <nuxt-link
                        to="/rules"
                        class="block p-3 -m-3 rounded-md hover:bg-gray-50"
                      >
                        <h5 class="text-base font-medium text-gray-900">
                          Rules
                        </h5>
                        <p class="mt-1 text-sm text-gray-500">
                          KTM Junior Racing official 2021 rules
                        </p>
                      </nuxt-link>
                    </div>
                  </div>
                </div>
              </transition>
            </div>
            <nuxt-link
              to="/registration"
              class="text-base font-medium text-white uppercase hover:text-ktmPrimary"
            >
              Registration
            </nuxt-link>
            <nuxt-link
              to="/calendar"
              class="text-base font-medium text-white uppercase hover:text-ktmPrimary"
            >
              Calendar
            </nuxt-link>
            <div class="relative">
              <button
                v-on-clickaway="closeParticipantsMenu"
                @click="participantsMenu = !participantsMenu"
                type="button"
                class="inline-flex items-center text-base font-medium text-white uppercase rounded-md group hover:text-ktmPrimary focus:outline-none"
              >
                <span>Participants</span>
                <svg
                  class="w-5 h-5 ml-2 text-gray-400 group-hover:text-white"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                    clip-rule="evenodd"
                  />
                </svg>
              </button>

              <transition
                enter-active-class="transition duration-200 ease-out"
                enter-class="translate-y-1 opacity-0"
                enter-to-class="translate-y-0 opacity-100"
                leave-active-class="transition duration-150 ease-in"
                leave-class="translate-y-0 opacity-100"
                leave-to-class="translate-y-1 opacity-0"
              >
                <div
                  v-show="participantsMenu"
                  class="absolute w-screen max-w-xs px-2 mt-3 transform -translate-x-1/2 left-1/2 sm:px-0"
                >
                  <div
                    class="overflow-hidden shadow-lg ring-1 ring-black ring-opacity-5"
                  >
                    <div
                      class="relative z-20 grid gap-6 px-5 py-6 bg-white sm:gap-8 sm:p-8"
                    >
                      <nuxt-link
                        to="/current-rider-list"
                        class="block p-3 -m-3 rounded-md hover:bg-gray-50"
                      >
                        <p class="text-base font-medium text-gray-900">
                          Current Rider List
                        </p>
                        <p class="mt-1 text-sm text-gray-500">
                          See all the riders participating in this years events
                        </p>
                      </nuxt-link>

                      <nuxt-link
                        to="/past-results"
                        class="block p-3 -m-3 rounded-md hover:bg-gray-50"
                      >
                        <p class="text-base font-medium text-gray-900">
                          Past Results
                        </p>
                        <p class="mt-1 text-sm text-gray-500">
                          Look at the results from all of the past KTM Junior
                          events
                        </p>
                      </nuxt-link>

                      <nuxt-link
                        to="/gallery"
                        class="block p-3 -m-3 rounded-md hover:bg-gray-50"
                      >
                        <p class="text-base font-medium text-gray-900">
                          Gallery
                        </p>
                        <p class="mt-1 text-sm text-gray-500">
                          Check out the photos from past KTM Junior Events - see
                          if you can find yourself!
                        </p>
                      </nuxt-link>
                    </div>
                  </div>
                </div>
              </transition>
            </div>
          </nav>
        </div>
        <div>
          <nuxt-link to="/" class="flex">
            <span class="sr-only">KTM JR</span>
            <img class="w-auto sm:h-40" src="~/assets/img/logo.jpg" alt="" />
          </nuxt-link>
        </div>
      </div>
    </div>

    <transition
      enter-active-class="transition duration-200 ease-out"
      enter-class="translate-y-1 opacity-0"
      enter-to-class="translate-y-0 opacity-100"
      leave-active-class="transition duration-150 ease-in"
      leave-class="translate-y-0 opacity-100"
      leave-to-class="translate-y-1 opacity-0"
    >
      <div
        v-show="mobileMenu"
        class="absolute inset-x-0 top-0 p-2 transition origin-top-right transform md:hidden"
      >
        <div
          class="bg-white divide-y-2 shadow-lg ring-1 ring-black ring-opacity-5 divide-gray-50"
        >
          <div class="px-5 pt-5 pb-6">
            <div class="flex items-center justify-end">
              <div class="-mr-2">
                <button
                  @click="mobileMenu = !mobileMenu"
                  type="button"
                  class="inline-flex items-center justify-end p-2 text-gray-400 bg-white rounded-md hover:text-white hover:bg-ktmPrimary focus:outline-none"
                >
                  <span class="sr-only">Close menu</span>
                  <svg
                    class="w-6 h-6"
                    xmlns="http://www.w3.org/2000/svg"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    aria-hidden="true"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M6 18L18 6M6 6l12 12"
                    />
                  </svg>
                </button>
              </div>
            </div>
            <div class="px-5 py-6">
              <div class="grid grid-cols-2 gap-4">
                <nuxt-link
                  to="/"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  Home
                </nuxt-link>
                <nuxt-link
                  to="/program-overview/about"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  About
                </nuxt-link>

                <nuxt-link
                  to="/faq"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  FAQ
                </nuxt-link>

                <nuxt-link
                  to="/rules"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  Rules
                </nuxt-link>

                <nuxt-link
                  to="/calendar"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  Calendar
                </nuxt-link>

                <nuxt-link
                  to="/about"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  Current Rider List
                </nuxt-link>

                <nuxt-link
                  to="/past-results"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  Past Results
                </nuxt-link>

                <nuxt-link
                  to="/gallery"
                  class="text-base font-medium text-gray-900 hover:text-gray-700"
                >
                  Gallery
                </nuxt-link>
              </div>
              <div class="mt-6">
                <nuxt-link
                  to="/registration"
                  class="flex items-center justify-center w-full px-4 py-2 text-base font-medium text-white border border-transparent rounded-md shadow-sm bg-ktmPrimary hover:bg-ktmPrimaryDark"
                >
                  Register Today!
                </nuxt-link>
                <p class="mt-6 text-base font-medium text-center text-gray-500">
                  Already applied?
                  <nuxt-link
                    to="/"
                    class="text-ktmPrimary hover:text-ktmPrimaryDark"
                  >
                    Check your code
                  </nuxt-link>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </transition>
  </header>
</template>

<script>
import { mixin as clickaway } from 'vue-clickaway'

export default {
  mixins: [clickaway],
  data() {
    return {
      programOverviewMenu: false,
      participantsMenu: false,
      mobileMenu: false
    }
  },
  methods: {
    closeProgramOverviewMenu() {
      this.programOverviewMenu = false
    },
    closeParticipantsMenu() {
      this.participantsMenu = false
    }
  }
}
</script>

<style>
a.nuxt-link-active,
.nuxt-link-active > h5 {
  color: #ff6600;
}
.programOverviewMenu {
  left: 160px;
}
</style>
