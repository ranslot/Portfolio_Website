<template>
  <div>
    <header class="bg-teal-200 shadow-xl rounded">
      <nav
        class="max-w-screen-2xl flex flex-wrap items-center justify-between mx-auto p-4"
      >
        <router-link to="/" class="flex items-start">
          <img src="../assets/Logo-icon.png" class="mr-2 h-10" />
        </router-link>
        <button
          @click="toggle"
          type="button"
          class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-teal-100 focus:outline-none focus:ring-2 focus:ring-teal-200"
          aria-controls="mainNavBar"
          aria-expanded="false"
        >
          <span class="sr-only">Open main menu</span>
          <svg
            class="w-6 h-6"
            aria-hidden="true"
            fill="currentColor"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
              clip-rule="evenodd"
            ></path>
          </svg>
        </button>
        <div
          :class="open ? 'block' : 'hidden'"
          class="w-full md:block md:w-auto"
          id="mainNavBar"
        >
          <ul
            class="font-medium flex flex-col p-0 mt-4 border border-gray-100 rounded-lg bg-teal-100 text-center md:flex-row md:space-x-8 md:mt-0 md:border-0"
          >
            <li>
              <router-link
                to="/"
                class="block py-2 pr-4 pl-3 text-black rounded"
                ><span>Home</span>
              </router-link>
            </li>
            <li>
              <router-link
                to="/about"
                class="block py-2 pr-4 pl-3 text-black rounded"
                ><span>About</span></router-link
              >
            </li>
            <li>
              <router-link
                to="/skills"
                class="block py-2 pr-4 pl-3 text-black rounded"
                ><span>Experiences</span></router-link
              >
            </li>
            <li>
              <router-link
                to="/projects"
                class="block py-2 pr-4 pl-3 text-black rounded"
                ><span>Projects</span></router-link
              >
            </li>
            <li>
              <router-link
                to="/contact"
                class="block py-2 pr-4 pl-3 text-black rounded"
                ><span>Contact</span></router-link
              >
            </li>
          </ul>
        </div>
      </nav>
    </header>
  </div>
</template>

<script>
export default {
  data() {
    return {
      open: false,
    };
  },
  methods: {
    toggle() {
      this.open = !this.open;
    },
  },
};
</script>
