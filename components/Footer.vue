<template>
  <div class="bg-indigo-400">
    <svg
      viewBox="0 0 1439 147"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
    >
      <g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
        <g transform="translate(-1.000000, -14.000000)" fill-rule="nonzero">
          <g class="wave" fill="white">
            <path
              d="M1440,84 C1383.555,64.3 1342.555,51.3 1317,45 C1259.5,30.824 1206.707,25.526 1169,22 C1129.711,18.326 1044.426,18.475 980,22 C954.25,23.409 922.25,26.742 884,32 C845.122,37.787 818.455,42.121 804,45 C776.833,50.41 728.136,61.77 713,65 C660.023,76.309 621.544,87.729 584,94 C517.525,105.104 484.525,106.438 429,108 C379.49,106.484 342.823,104.484 319,102 C278.571,97.783 231.737,88.736 205,84 C154.629,75.076 86.296,57.743 0,32 L0,0 L1440,0 L1440,84 Z"
            />
          </g>
          <g transform="translate(1.000000, 15.000000)" fill="#FFFFFF">
            <g
              transform="translate(719.500000, 68.500000) rotate(-180.000000) translate(-719.500000, -68.500000) "
            >
              <path
                d="M0,0 C90.7283404,0.927527913 147.912752,27.187927 291.910178,59.9119003 C387.908462,81.7278826 543.605069,89.334785 759,82.7326078 C469.336065,156.254352 216.336065,153.6679 0,74.9732496"
                opacity="0.100000001"
              />
              <path
                d="M100,104.708498 C277.413333,72.2345949 426.147877,52.5246657 546.203633,45.5787101 C666.259389,38.6327546 810.524845,41.7979068 979,55.0741668 C931.069965,56.122511 810.303266,74.8455141 616.699903,111.243176 C423.096539,147.640838 250.863238,145.462612 100,104.708498 Z"
                opacity="0.100000001"
              />
              <path
                d="M1046,51.6521276 C1130.83045,29.328812 1279.08318,17.607883 1439,40.1656806 L1439,120 C1271.17211,77.9435312 1140.17211,55.1609071 1046,51.6521276 Z"
                opacity="0.200000003"
              />
            </g>
          </g>
        </g>
      </g>
    </svg>
    <div
      class="w-full py-4 text-sm text-center md:text-left fade-in container mx-auto text-white p-8 lg:flex flex-wrap justify-center items-center"
    >
      <div class="flex-1 lg:pr-8">
        <p class="pb-2 font-bold">{{ $t('home.download') }}</p>
        <div class="lg:flex flex-wrap">
          <div class="pb-2 lg:pr-2">
            <a
              href="https://play.google.com/store/apps/details?id=org.banderablanca"
              target="_blank"
            >
              <img src="~/assets/img/Play Store.svg" class="h-12 bounce-top-icons mx-auto" />
            </a>
          </div>
          <a href="https://apps.apple.com/pe/app/bandera-blanca/id1507865656">
            <img src="~/assets/img/App Store.svg" class="h-12 lg:pr-4 bounce-top-icons mx-auto" />
          </a>
        </div>
      </div>
      <div class="flex-1 lg:pr-8">
        <!-- <p class="pb-2 font-bold pt-8 lg:pt-0">INTEGRANTES</p>
        <div class=" flex-wrap lg:flex">
          <ul class="lg:pl-4">
            <li class="font-light flex flex-wrap">
              • Henry - <span class="font-bold"></span>
            </li>
            <li class="font-light flex flex-wrap">
              • Angy Quispe - <span class="font-bold"></span>
            </li>
          </ul>
          <ul class="lg:pl-6">
            <li class="font-light flex flex-wrap">
              • Edgar Huamaní - <span class="font-bold"></span>
            </li>
            <li class="font-light flex flex-wrap">
              • Katherine Azabache - <span class="font-bold"></span>
            </li>
          </ul>
          <ul class="lg:pl-6">
            <li class="font-light flex flex-wrap">
              • Johny Ronald - <span class="font-bold"></span>
            </li>
            <li class="font-light flex flex-wrap">
              • Melanie - <span class="font-bold"></span>
            </li>
          </ul>
          <ul class="lg:pl-6">
            <li class="font-light flex flex-wrap">
              • Guillermo - <span class="font-bold"></span>
            </li>
            <li class="font-light flex flex-wrap">
              • Mario André - <span class="font-bold"></span>
            </li>
          </ul>
        </div>-->
      </div>
      <div class="flex-1 lg:w-1/3 lg:pr-8">
        <div class="flex justify-end">
          <a
            href="https://www.facebook.com/BanderaBlancaApp/"
            target="_blank"
            class="text-spaceblue-300"
          >
            <font-awesome-icon :icon="['fab', 'facebook']" />&nbsp; BanderaBlancaApp
          </a>
          <!-- <a
            href=""
            target="_blank"
            class="text-spaceblue-300 mx-2"
          >
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
              <path
                d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"
              />
            </svg>
          </a>
          <a href="" target="_blank" class="text-spaceblue-300">
            <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" class="w-6 h-6">
              <path
                d="M23.954 4.569c-.885.389-1.83.654-2.825.775 1.014-.611 1.794-1.574 2.163-2.723-.951.555-2.005.959-3.127 1.184-.896-.959-2.173-1.559-3.591-1.559-2.717 0-4.92 2.203-4.92 4.917 0 .39.045.765.127 1.124C7.691 8.094 4.066 6.13 1.64 3.161c-.427.722-.666 1.561-.666 2.475 0 1.71.87 3.213 2.188 4.096-.807-.026-1.566-.248-2.228-.616v.061c0 2.385 1.693 4.374 3.946 4.827-.413.111-.849.171-1.296.171-.314 0-.615-.03-.916-.086.631 1.953 2.445 3.377 4.604 3.417-1.68 1.319-3.809 2.105-6.102 2.105-.39 0-.779-.023-1.17-.067 2.189 1.394 4.768 2.209 7.557 2.209 9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63.961-.689 1.8-1.56 2.46-2.548l-.047-.02z"
              />
            </svg>
          </a>-->
        </div>
      </div>
    </div>

    <div class="bg-gray-800 p-4 text-center text-white">
      <p>
        No hay nada más fuerte en el mundo que el corazón de un voluntario.
        <span
          class="font-bold"
        >Coronel James H. Doolittle</span>
      </p>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'Footer'
})
</script>
