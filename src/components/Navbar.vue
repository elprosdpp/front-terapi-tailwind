<template>
  <div>
    <nav class="bg-white border-gray-200 dark:bg-gray-900 my-5">
      <!-- Logo  -->
      <div
        class="flex flex-wrap justify-center items-center mx-auto max-w-screen-xl px-4 md:px-6 py-2.5 lg:justify-between"
      >
        <router-link to="/" class="flex items-center mb-2 lg:mb-0">
          <img class="w-12 mr-2" src="../assets/img/unw.png" alt="" />
          <div class="flex flex-col justify-start items-start">
            <h1 class="hidden md:block lg:block text-[1rem] font-bold text-dLink">
              KERJASAMA DAN ALUMNI
            </h1>
            <h1 class="hidden md:block lg:block text-[1rem] font-bold text-dLink">
              UNIVERSITAS NGUDI WALUYO
            </h1>
            <h1 class="block md:hidden lg:hidden text-[1.4rem] font-bold text-dLink">
              KERJASAMA UNW
            </h1>
          </div>
        </router-link>
        <div class="flex items-center">
          <p class="mt-2 text-dBlue text-center font-bold text-sm lg:mt-0 lg:text-right">
            Universitas Unggul, Berbudaya Sehat dan, Bereputasi Internasional
          </p>
        </div>
      </div>

      <!-- End Logo -->
    </nav>
    <hr class="border-navy" />
    <nav class="dark:bg-gray-700 my-1">
      <div class="py-3 px-4 mx-auto max-w-screen-xl md:px-6">
        <div class="flex items-center justify-center lg:justify-between">
          <ul class="flex flex-row mt-0 space-x-8 text-sm font-medium">
            <li>
              <a href="#" class="text-dLink font-bold" aria-current="page">BERANDA</a>
            </li>
            <li>
              <a href="#" class="text-dLink font-bold" aria-current="page">BERANDA</a>
            </li>
            <li>
              <a href="#" class="text-dLink font-bold" aria-current="page">BERANDA</a>
            </li>
            <li>
              <a href="#" class="text-dLink font-bold" aria-current="page">BERANDA</a>
            </li>
          </ul>
          <div class="hidden md:flex lg:flex items-center">
            <form>
              <label
                for="default-search"
                class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-gray-300"
                >Search</label
              >
              <div class="relative">
                <div
                  class="flex absolute inset-y-0 left-0 items-center pl-3 pointer-events-none"
                >
                  <svg
                    aria-hidden="true"
                    class="w-5 h-5 text-gray-500 dark:text-gray-400"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                    ></path>
                  </svg>
                </div>
                <input
                  type="search"
                  id="default-search"
                  class="block p-3 pl-10 w-full text-sm text-gray-900 bg-gray-50 rounded-lg border border-gray-300 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                  placeholder="Search Dokumen/MoU/Kegiatan"
                  required
                />
              </div>
            </form>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
