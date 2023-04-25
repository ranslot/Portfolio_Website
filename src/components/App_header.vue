<template>
  <div>
    <header class="bg-white border-gray-200 dark:bg-gray-200">
      <nav class="flex flex-wrap justify-between px-10 py-3">
        <a href="https://flowbite.com" class="flex items-start">
          <img
            src="https://flowbite.com/docs/images/logo.svg"
            class="mr-3 h-6 sm:h-9"
            alt="Flowbite Logo"
          />
          <span class="self-center text-xl font-semibold whitespace-nowrap"
            >Supagrit's Portfolio</span
          >
        </a>
        <ul
          class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg:mt-0 flow"
        >
          <li>
            <router-link to="/" class="block py-2 pr-4 pl-3 text-black rounded"
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
              ><span>Skill</span></router-link
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
      </nav>
    </header>
  </div>
</template>

<script>
export default {};
</script>
