<template>
  <main class="pb-24 bg-gray-100">
    <section class="mx-auto max-w-screen-2xl">
      <img src="~/assets/img/hero.jpg" alt="KTM JR Register Banner" />
    </section>
    <section class="px-4 mx-auto mt-12 max-w-7xl sm:mt-24 sm:px-6 lg:px-8">
      <div class="relative z-10 mb-8 md:mb-2 md:px-6">
        <div class="text-base max-w-prose lg:max-w-none">
          <h4
            class="font-semibold leading-6 tracking-wide uppercase text-ktmPrimary"
          >
            OFFICIAL KTM JUNIOR RACING PROGRAM 2021
          </h4>
          <h2
            class="mt-2 text-3xl font-extrabold leading-8 tracking-tight text-gray-900 sm:text-4xl"
          >
            Application Information
          </h2>
          <div class="max-w-screen-lg mt-8 prose-lg text-gray-800">
            <p>
              Thank you for your interest in the KTM JUNIOR RACING program. This
              is truly a unique opportunity for your child to experience life as
              a professional racer for a day! Below you will find the official
              rules, the KTM JUNIOR RACING event schedule and application form.
              Please read through all the information carefully.
            </p>
            <p>
              For the safety of all riders, the rider applying for the program
              must have at least one year of racing experience to be eligible.
              Today's Supercross tracks are not playgrounds and present very
              challenging riding conditions. To make sure the KTM JUNIOR RACING
              experience is a positive one, every parent should strongly
              evaluate whether or not their child's riding skills are up to the
              challenge.
            </p>
          </div>
        </div>
      </div>
      <div class="relative md:p-6">
        <div class="lg:grid lg:grid-cols-2 lg:gap-6">
          <div class="mt-6 prose prose-lg text-gray-800 lg:mt-0">
            <p>
              How the application process works:
            </p>
            <ol>
              <li>
                Get yourself familiar with the rules and information. (links to
                rules page)
              </li>
              <li>
                Complete the 2021 Application in full and include all
                supplemental materials.
              </li>
              <li>
                Qualified applicants will be selected at random. A drawing to
                determine final contestants will be conducted 4 weeks before
                selected event.
              </li>
              <li>
                All applicants will be notified at least 3 weeks prior to the
                event. Those picked will receive detailed instructions regarding
                race day procedures.
              </li>
              <li>
                Please be sure to check the box for all rounds you are
                interested in racing.
              </li>
              <li>
                KTM JUNIOR RACING Participants and mechanics must be current
                American Motorcyclist Association (AMA) members on the day of
                the event to receive track-access passes. AMA memberships can be
                purchased and/or renewed at the event, or you can ask your KTM
                dealer how to contact the AMA for memberships.
              </li>
            </ol>
          </div>
          <div class="prose prose-lg text-gray-800 lg:max-w-none">
            <p>If selected, riders will:</p>
            <ul>
              <li>Pay a $300 (US) entry fee</li>
              <li>
                Receive a complete KTM x Troy Lee Designs riding outfit (pants,
                jersey, gloves)
              </li>
              <li>
                Receive a KTM JUNIOR RACING Participation Certificate
              </li>
              <li>
                Receive 4 complimentary passes (1 rider/1 mechanic/ 2
                complimentary passes)
              </li>
              <li>
                Receive a day experiencing the "Factory Rider Treatment"
              </li>
              <li>
                Arrive at the Supercross location on Saturday morning for
                registration and practice
              </li>
              <li>
                Participate in the KTM JUNIOR RACING race during the
                intermission of Saturday night's main event
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <section class="max-w-6xl px-4 mx-auto mt-12 sm:mt-24 sm:px-6 lg:px-8">
      <h2 class="mb-20 text-4xl">
        Official KTM Junior Racing Program 2021 Application
      </h2>
      <form id="sign-up-form" action="#" method="POST">
        <div>
          <div class="md:grid md:grid-cols-3 md:gap-6">
            <div class="md:col-span-1">
              <div class="px-4 sm:px-0">
                <h3 class="text-lg font-medium leading-6 text-gray-900">
                  Parent Information
                </h3>
                <p class="mt-1 text-gray-600">
                  This information needs to be filled out by the legal guardian
                  of the applicant
                </p>
              </div>
            </div>
            <div class="mt-5 md:mt-0 md:col-span-2">
              <div class="overflow-hidden shadow sm:rounded-md">
                <div class="px-4 py-5 bg-white sm:p-6">
                  <div class="grid grid-cols-6 gap-6">
                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="parent_first_name"
                        class="block text-sm font-medium text-gray-700"
                        >Parent's First Name</label
                      >
                      <input
                        type="text"
                        id="parent_first_name"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                        required
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="parent_last_name"
                        class="block text-sm font-medium text-gray-700"
                        >Parent's Last Name</label
                      >
                      <input
                        type="text"
                        id="parent_last_name"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                        required
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="parent_last_name"
                        class="block text-sm font-medium text-gray-700"
                        >Parent's Last Name</label
                      >
                      <input
                        type="text"
                        id="parent_last_name"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                        required
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="parent_last_name"
                        class="block text-sm font-medium text-gray-700"
                        >Parent's Last Name</label
                      >
                      <input
                        type="text"
                        id="parent_last_name"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                        required
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="parents_shirt_size"
                        class="block text-sm font-medium text-gray-700"
                        >Parent’s Shirt Size</label
                      >
                      <select
                        id="parents_shirt_size"
                        class="block w-full px-3 py-2 mt-1 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                        required
                      >
                        <option selected disabled>Choose a size: </option>
                        <option>Small</option>
                        <option>Medium</option>
                        <option>Large</option>
                        <option>XL</option>
                        <option>2XL</option>
                        <option>3XL</option>
                      </select>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="hidden sm:block" aria-hidden="true">
          <div class="py-5">
            <div class="border-t border-gray-200"></div>
          </div>
        </div>

        <div class="mt-10 sm:mt-0">
          <div class="md:grid md:grid-cols-3 md:gap-6">
            <div class="md:col-span-1">
              <div class="px-4 sm:px-0">
                <h3 class="text-lg font-medium leading-6 text-gray-900">
                  Rider Information
                </h3>
                <p class="mt-1 text-gray-600">
                  This information needs to be filled out by the legal guardian
                  of the applicant
                </p>
              </div>
            </div>
            <div class="mt-5 md:mt-0 md:col-span-2">
              <div class="overflow-hidden shadow sm:rounded-md">
                <div class="px-4 py-5 bg-white sm:p-6">
                  <div class="grid grid-cols-6 gap-6">
                    <div class="col-span-6 sm:col-span-3">
                      <label
                        id="first_name"
                        for="first_name"
                        class="block text-sm font-medium text-gray-700"
                        >First name</label
                      >
                      <input
                        type="text"
                        id="first_name"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        id="value"
                        for="last_name"
                        class="block text-sm font-medium text-gray-700"
                        >Last name</label
                      >
                      <input
                        type="text"
                        id="last_name"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        id="value"
                        for="country"
                        class="block text-sm font-medium text-gray-700"
                        >Country / Region</label
                      >
                      <select
                        id="country"
                        class="block w-full px-3 py-2 mt-1 bg-white border border-gray-300 rounded-md shadow-sm focus:outline-none focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      >
                        <option>United States</option>
                        <option>Canada</option>
                        <option>Mexico</option>
                      </select>
                    </div>

                    <div class="col-span-6">
                      <label
                        id="value"
                        for="street_address"
                        class="block text-sm font-medium text-gray-700"
                        >Street address</label
                      >
                      <input
                        type="text"
                        id="street_address"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-6 lg:col-span-2">
                      <label
                        id="valussssse"
                        for="city"
                        class="block text-sm font-medium text-gray-700"
                        >City</label
                      >
                      <input
                        type="text"
                        id="city"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                      <label
                        id="valuesssss"
                        for="state"
                        class="block text-sm font-medium text-gray-700"
                        >State / Province</label
                      >
                      <input
                        type="text"
                        id="state"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3 lg:col-span-2">
                      <label
                        id="value"
                        for="postal_code"
                        class="block text-sm font-medium text-gray-700"
                        >ZIP / Postal</label
                      >
                      <input
                        type="text"
                        id="postal_code"
                        class="block w-full mt-1 border-gray-300 rounded-md focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="hidden sm:block" aria-hidden="true">
          <div class="py-5">
            <div class="border-t border-gray-200"></div>
          </div>
        </div>

        <div class="mt-10 sm:mt-0">
          <div class="md:grid md:grid-cols-3 md:gap-6">
            <div class="md:col-span-1">
              <div class="px-4 sm:px-0">
                <h3 class="text-lg font-medium leading-6 text-gray-900">
                  Rider Submissions
                </h3>
                <p class="mt-1 text-gray-600">
                  Please upload the a copy of the rider’s birth certificate, a
                  scan of the riders most recent report card, a profile image,
                  the rider’s AMA number, and three videos that show a gate
                  drop, riding over an obstacle, and a brief introduction
                </p>
              </div>
            </div>
            <div class="mt-5 md:mt-0 md:col-span-2">
              <form action="#" method="POST">
                <div class="shadow sm:rounded-md sm:overflow-hidden">
                  <div class="px-4 py-5 space-y-6 bg-white sm:p-6">
                    <div>
                      <label class="block text-sm font-medium text-gray-700">
                        Photo
                      </label>
                      <div class="flex items-center mt-2">
                        <span
                          class="inline-block w-12 h-12 overflow-hidden bg-gray-100 rounded-full"
                        >
                          <svg
                            class="w-full h-full text-gray-300"
                            fill="currentColor"
                            viewBox="0 0 24 24"
                          >
                            <path
                              d="M24 20.993V24H0v-2.996A14.977 14.977 0 0112.004 15c4.904 0 9.26 2.354 11.996 5.993zM16.002 8.999a4 4 0 11-8 0 4 4 0 018 0z"
                            />
                          </svg>
                        </span>
                        <button
                          type="button"
                          class="px-3 py-2 ml-5 text-sm font-medium leading-4 text-gray-700 bg-white border border-gray-300 rounded-md shadow-sm hover:bg-gray-50 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ktmPrimary"
                        >
                          Change
                        </button>
                      </div>
                    </div>

                    <div>
                      <label
                        for="about"
                        class="block text-sm font-medium text-gray-700"
                      >
                        About
                      </label>
                      <div class="mt-1">
                        <textarea
                          id="about"
                          rows="3"
                          class="block w-full mt-1 border-gray-300 rounded-md shadow-sm focus:ring-ktmPrimary focus:border-ktmPrimaryDark sm:text-sm"
                          placeholder="you@example.com"
                        ></textarea>
                      </div>
                      <p class="mt-2 text-sm text-gray-500">
                        Brief description for your profile. URLs are
                        hyperlinked.
                      </p>
                    </div>

                    <div>
                      <label class="block text-sm font-medium text-gray-700">
                        Birth Certificate Image
                      </label>
                      <div
                        class="flex justify-center px-6 pt-5 pb-6 mt-2 border-2 border-gray-300 border-dashed rounded-md"
                      >
                        <div class="space-y-1 text-center">
                          <svg
                            class="w-12 h-12 mx-auto text-gray-400"
                            stroke="currentColor"
                            fill="none"
                            viewBox="0 0 48 48"
                            aria-hidden="true"
                          >
                            <path
                              d="M28 8H12a4 4 0 00-4 4v20m32-12v8m0 0v8a4 4 0 01-4 4H12a4 4 0 01-4-4v-4m32-4l-3.172-3.172a4 4 0 00-5.656 0L28 28M8 32l9.172-9.172a4 4 0 015.656 0L28 28m0 0l4 4m4-24h8m-4-4v8m-12 4h.02"
                              stroke-width="2"
                              stroke-linecap="round"
                              stroke-linejoin="round"
                            />
                          </svg>
                          <p class="text-sm text-gray-600">
                            <button
                              class="font-medium bg-white rounded-md text-ktmPrimary hover:text-indigo-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ktmPrimary"
                            >
                              Upload a file
                            </button>
                            or drag and drop
                          </p>
                          <p class="text-xs text-gray-500">
                            PNG, JPG, GIF up to 10MB
                          </p>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>

        <div class="hidden sm:block" aria-hidden="true">
          <div class="py-5">
            <div class="border-t border-gray-200"></div>
          </div>
        </div>

        <div class="mt-10 sm:mt-0">
          <div class="md:grid md:grid-cols-3 md:gap-6">
            <div class="md:col-span-1">
              <div class="px-4 sm:px-0">
                <h3 class="text-lg font-medium leading-6 text-gray-900">
                  Event List
                </h3>
                <p class="mt-1 text-gray-600">
                  Please be sure to check the box for all rounds you are
                  interested in racing.
                </p>
              </div>
            </div>
            <div class="mt-5 md:mt-0 md:col-span-2">
              <form action="#" method="POST">
                <div class="overflow-hidden shadow sm:rounded-md">
                  <div class="px-4 py-5 space-y-6 bg-white sm:p-6">
                    <fieldset>
                      <legend class="text-base font-medium text-gray-900">
                        Enter below
                      </legend>
                      <div class="mt-4 space-y-4">
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="comments"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="comments"
                              class="font-medium text-gray-700"
                              >JANUARY 16 - NRG Stadium | Houston, TX
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: December 18, 2020
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="candidates"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="candidates"
                              class="font-medium text-gray-700"
                              >JANUARY 23 - NRG Stadium | Houston, TX
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: December 25, 2020
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >JANUARY 30 - Lucas Oil Stadium | Indianapolis, IN
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: January 1, 2021
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >FEBRUARY 20 - State Farm Stadium | Glendale, AZ
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: January 22, 2021
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >FEBRUARY 27 - State Farm Stadium | Glendale, AZ
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: January 29, 2021
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >MARCH 20 - AT&T Stadium | Arlington, TX
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: February 19, 2021
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >MARCH 27 - AT&T Stadium | Arlington, TX</label
                            >
                            <p class="text-gray-500">
                              Registration Deadline: February 26, 2021
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >ROUND 8 - TBD</label
                            >
                            <p class="text-gray-500">
                              Registration Deadline: TBD
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >ROUND 9 - TBD
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: TBD
                            </p>
                          </div>
                        </div>
                        <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input
                              id="offers"
                              type="checkbox"
                              class="w-4 h-4 border-gray-300 rounded text-ktmPrimary focus:ring-ktmPrimary"
                            />
                          </div>
                          <div class="ml-3 text-sm">
                            <label
                              for="offers"
                              class="font-medium text-gray-700"
                              >ROUND 10 - Rice-Eccles Stadium | Salt Lake City,
                              UT
                            </label>
                            <p class="text-gray-500">
                              Registration Deadline: TBD
                            </p>
                          </div>
                        </div>
                      </div>
                    </fieldset>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>

        <div class="hidden sm:block" aria-hidden="true">
          <div class="py-5">
            <div class="border-t border-gray-200"></div>
          </div>
        </div>

        <div class="max-w-screen-md prose text-gray-800">
          <p class="font-bold">
            IF YOUR CHILD HAS NEVER RACED, PLEASE DO NOT APPLY BECAUSE A MONSTER
            ENERGY SUPERCROSS TRACK IS NOT IDEAL FOR A FIRST-TIME-RACING
            EXPERIENCE.
          </p>
          <p class="font-bold">
            THERE MAY BE CIRCUMSTANCES (SUCH AS WEATHER, TRACK CONDITIONS AND
            SAFETY ISSUES) THAT MAY FORCE FELD MOTOR SPORTS, INC AND KTM TO
            ALTER THE SCHEDULE, THE COURSE, OR CANCEL AN EVENT. FELD MOTOR
            SPORTS, INC AND KTM RESERVE THE RIGHT TO ADJUST THE SCHEDULE AS THEY
            SEE FIT.
          </p>
          <p>
            Parents: If your child has participated in a KTM JUNIOR RACING event
            before, they are not eligible to enter again. This year, KTM JUNIOR
            RACING participants will ride the 2021 KTM SX-E 5. Before completing
            the entry form, please be sure your child would like to participate
            in this event. It may sound like the chance of a lifetime for you
            and be a nightmare to your child. Consider that your child will be
            in front of 50,000 spectators riding over LARGE and technical
            obstacles. We want this to be a positive experience for your child.
            Also, consider your role in this event. KTM JUNIOR RACING is
            intended to be a fun event with the emphasis on sportsmanship.
            Abusive, high-pressure tactics will get you, and unfortunately your
            child, ejected immediately.
          </p>
          <p>
            Thank you for your application and interest in KTM North America and
            the KTM JUNIOR RACING program!
          </p>
        </div>

        <div class="mt-12 text-right">
          <button
            type="submit"
            class="inline-flex justify-center px-4 py-2 font-medium text-white uppercase border border-transparent shadow-sm bg-ktmPrimary hover:bg-ktmPrimaryDark focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-ktmPrimary"
          >
            Submit
          </button>
        </div>
      </form>
    </section>
  </main>
</template>

<script>
export default {}
</script>
