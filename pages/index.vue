<template>
  <main>
    <section class="mx-auto max-w-screen-2xl">
      <img src="~/assets/img/hero.jpg" alt="KTM JR Register Banner" />
    </section>
    <section class="px-4 mx-auto mt-12 sm:mt-24 max-w-7xl sm:px-6 lg:px-8">
      <div class="grid gap-8 lg:grid-cols-2">
        <div class="col-span-1 overflow-hidden bg-white rounded-lg shadow">
          <div class="px-4 py-5 space-y-4 sm:p-6">
            <p>Dear KTM Junior Supercross Racing applicants,</p>
            <p>
              Due to the ongoing COVID-19 situation, and the cancellation of
              select 2020 Supercross events, rounds 8-10 of the KTM Junior
              Racing series have been cancelled. As we await rescheduled event
              confirmation from our partners at FELD and the American
              Motorcyclist Association, the rider selection for the final three
              rounds has been postponed. This applies to current and new
              applicants. We will continue to publish updates as things return
              to normal.
            </p>
            <p>
              We appreciate your patience as we navigate through this
              postponement.
            </p>
          </div>
        </div>
        <div class="col-span-1 overflow-hidden bg-white rounded-lg shadow">
          <div class="px-4 py-5 sm:p-6">
            <h2 class="text-4xl font-bold uppercase">Already Applied?</h2>
            <p>Check your status by entering your registration code</p>
            <form class="mt-6">
              <label for="registration" class="sr-only">Registration</label>
              <div class="flex mt-1 rounded-md shadow">
                <div
                  class="relative flex items-stretch flex-grow focus-within:z-10"
                >
                  <div
                    class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none"
                  ></div>
                  <input
                    type="number"
                    id="registration"
                    class="block w-full py-2 pl-4 border-gray-300 rounded-none focus:ring-indigo-500 focus:border-indigo-500 rounded-l-md sm:text-lg"
                    placeholder="Enter your code here"
                    required
                  />
                </div>
                <button
                  class="relative inline-flex items-center px-4 py-2 -ml-px space-x-2 text-sm font-bold text-white uppercase border border-gray-300 rounded-r-md bg-ktmPrimary hover:bg-ktmPrimaryDark focus:outline-none focus:ring-1 focus:ring-indigo-500 focus:border-indigo-500"
                >
                  Submit
                </button>
              </div>
            </form>

            <p class="mt-2 text-xs">
              Don’t remember your code? Click
              <a href="#" class="text-ktmPrimary">here</a> to retrieve it!
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="px-4 mx-auto mt-12 sm:mt-24 max-w-7xl sm:px-6 lg:px-8">
      <h2 class="text-3xl font-bold text-center uppercase">Our Sponsors</h2>
      <img
        src="~/assets/img/sponsors.jpg"
        alt="KTM JR Register Banner"
        class="mx-auto mt-8 md:max-w-screen-md"
      />
    </section>
  </main>
</template>

<script>
export default {}
</script>
