<script setup></script>

<template>
  <main>
    <div
      class="-mt-24 lg:-mt-32 relative w-screen h-60 lg:h-96 bg-green-500 overflow-hidden"
    >
      <img src="/united-polytechnic-gate.jpeg" class="w-full" />
    </div>
    <div
      class="w-11/12 lg:w-10/12 relative text-sm -mt-28 mb-48 lg:-mt-56 lg:mb-56 mx-auto drop-shadow-lg"
    >
      <div
        class="item-1 -ml-28 lg:-ml-40 w-96 bg-white p-4 rounded-lg shadow-lg drop-shadow-lg"
      >
        <h2 class="text-lg lg:text-3xl text-blue-600 font-bold">Welcome.</h2>
        <p class="mt-3 border-l-4 border-red-600 pl-3 rounded">
          United Polytechnic (former United School of Science & Technology) is
          accredited by NBTE and licensed by Federal Ministry of Education.
        </p>
        <div class="mt-4 text-right">
          <RouterLink
            to="/"
            class="bg-red-600 text-white text-xs py-2 px-3 rounded-full hover:opacity-60"
            >About United Polytechnic</RouterLink
          >
        </div>
      </div>
      <div
        class="item-2 -ml-28 lg:-ml-40 w-96 bg-white p-4 rounded-lg shadow-lg drop-shadow-lg"
      >
        <h2 class="text-lg lg:text-3xl text-blue-600 font-bold">Apply.</h2>
        <p class="mt-3 border-l-4 border-red-600 pl-3 rounded">
          Apply to study at United Polytechnic today for a Quality and
          Innovative Education in the Field of Technical & Business Education.
        </p>
        <div class="mt-4 text-right">
          <RouterLink
            to="/"
            class="bg-red-600 text-white text-xs py-2 px-3 rounded-full hover:opacity-60"
            >Apply</RouterLink
          >
        </div>
      </div>
      <div
        class="item-3 -ml-28 lg:-ml-40 w-96 bg-white p-4 rounded-lg shadow-lg drop-shadow-lg"
      >
        <h2 class="text-lg lg:text-3xl text-blue-600 font-bold">
          Excellent Curriculum.
        </h2>
        <p class="mt-3 border-l-4 border-red-600 pl-3 rounded">
          Our curriculum was designed to achieve high academic standards in
          teaching and learning.
        </p>
        <div class="mt-4 text-right">
          <RouterLink
            to="/"
            class="bg-red-600 text-white text-xs py-2 px-3 rounded-full hover:opacity-60"
            >See Programmes</RouterLink
          >
        </div>
      </div>
    </div>
    <div class="bg-blue-600 py-3 text-base">
      <div
        class="flex flex-col space-y-1 lg:space-y-0 lg:flex-row w-11/12 lg:w-10/12 mx-auto text-white lg:space-x-2"
      >
        <span>
          <span class="bg-black font-normal p-1">Top News:</span>
        </span>
        <span class=""
          >Application forms are currently on sale.
          <a href="/" class="border-b border-dashed"
            >Click here for details</a
          ></span
        >
      </div>
    </div>
    <div class="w-11/12 lg:w-10/12 mx-auto mt-10 lg:mt-20">
      <h2 class="text-center font-bold text-xl lg:text-2xl text-green-700">
        More School News & Events
      </h2>
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-4 mt-3">
        <div class="bg-gray-300 h-44 lg:h-60">&nbsp;</div>
        <div class="bg-gray-300 h-44 lg:h-60">&nbsp;</div>
        <div class="bg-gray-300 h-44 lg:h-60">&nbsp;</div>
        <div class="bg-gray-300 h-44 lg:h-60">&nbsp;</div>
      </div>
      <div class="text-right pt-8">
        <RouterLink
          to="/"
          class="bg-red-600 text-xs rounded-full p-3 text-white hover:opacity-60"
          >Go to News Page</RouterLink
        >
      </div>
    </div>
    <div
      class="w-11/12 lg:w-10/12 mx-auto bg-white shadow-xl border-t rounded-lg p-2 lg:p-12 mt-20 lg:mt-40"
    >
      <div
        class="w-full lg:w-9/12 mx-auto grid grid-cols-1 gap-8 lg:grid-cols-2 lg:gap-20"
      >
        <div class="bg-white border-2 border-blue-950 pb-4">
          <div class="h-36 overflow-hidden">
            <img src="/handbook.jpg" class="w-full z-10" />
          </div>
          <h2 class="bg-red-600 p-1 text-center font-bold text-white">
            Student Handbook/brochure
          </h2>
          <p class="text-lg leading-snug text-gray-700 p-3">
            Download our student handbook for more information.
          </p>
          <p class="p-3 text-center">
            <RouterLink
              to="/"
              class="text-lg font-bold text-blue-500 border shadow-lg p-3 uppercase text-center hover:opacity-60"
              >Download &rarr;</RouterLink
            >
          </p>
        </div>
        <div class="bg-white border-2 border-blue-950 pb-4">
          <div class="h-36 overflow-hidden">
            <img src="/accommodation-info.jpeg" class="w-full z-10" />
          </div>
          <h2 class="bg-red-600 p-1 text-center font-bold text-white">
            Accommodation Information
          </h2>
          <p class="text-lg leading-snug text-gray-700 p-3">
            Good and conducive accommodation/hostel facilities are available.
          </p>
          <p class="p-3 text-center">
            <RouterLink
              to="/"
              class="text-lg font-bold text-blue-500 border shadow-lg p-3 uppercase text-center hover:opacity-60"
              >Learn more &rarr;</RouterLink
            >
          </p>
        </div>
      </div>
    </div>
    <div class="mt-20 lg:mt-40 grid grid-cols-1 lg:grid-cols-2 bg-green-100">
      <div class="overflow-hidden">
        <img src="/unitech-oath.jpg" class="w-full" />
      </div>
      <div class="p-8">
        <h2 class="text-xl lg:text-2xl text-green-700 font-semibold">
          Our Philosophy
        </h2>
        <p class="mt-4 text-sm">
          United School of Science and Technology was established to create
          opportunities for students and members of departments to participate
          in the long established and worldwide tradition of academic excellence
          for the propagation of knowledge and preservation of the school
          commitment to the understanding of humanity with its concomitant
          concern for unraveling the nature of phenomena which man seeks to
          domesticate.
        </p>
      </div>
    </div>
  </main>
</template>

<style scoped>
.item-1,
.item-2,
.item-3 {
  position: absolute;
  display: block;
  /* top: 2em; */

  /* width: 60%; */

  /* font-size: 2em; */

  animation-duration: 20s;
  animation-timing-function: ease-in-out;
  animation-iteration-count: infinite;
}

.item-1 {
  animation-name: anim-1;
}

.item-2 {
  animation-name: anim-2;
}

.item-3 {
  animation-name: anim-3;
}

@keyframes anim-1 {
  0%,
  8.3% {
    left: -100%;
    opacity: 0;
  }
  8.3%,
  25% {
    left: 25%;
    opacity: 1;
  }
  33.33%,
  100% {
    left: 110%;
    opacity: 0;
  }
}

@keyframes anim-2 {
  0%,
  33.33% {
    left: -100%;
    opacity: 0;
  }
  41.63%,
  58.29% {
    left: 25%;
    opacity: 1;
  }
  66.66%,
  100% {
    left: 110%;
    opacity: 0;
  }
}

@keyframes anim-3 {
  0%,
  66.66% {
    left: -100%;
    opacity: 0;
  }
  74.96%,
  91.62% {
    left: 25%;
    opacity: 1;
  }
  100% {
    left: 110%;
    opacity: 0;
  }
}
</style>
