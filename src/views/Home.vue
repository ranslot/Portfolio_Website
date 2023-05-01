<template>
  <div class="p-7">
    <section class="hero flex flex-col lg:flex-row justify-evenly">
      <img
        src="../assets/Logo-icon.png"
        alt=""
        width="362"
        height="385"
        class="mx-auto"
      />
      <p class="lg:my-auto mx-auto mt-5">
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
      </p>
    </section>
    <section class="mt-10">
      <article class="border-2 rounded border-black m-10 p-4 overflow-auto">
        <h2 class="font-bold text-lg">About Me</h2>
        <p class="text-sm md:text-base">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores earum
          ex provident pariatur mollitia corporis, laborum ratione recusandae,
          iste deserunt ab officiis consequuntur. Nostrum autem facere cum
          voluptatum consequuntur dolorem.
        </p>
        <div class="max-w-fit m-3 float-right">
          <router-link
            to="/about"
            class="px-3 py-2 rounded-lg bg-green-300 text-gray-500"
            >Read more</router-link
          >
        </div>
      </article>
      <article class="border-2 rounded border-black m-10 p-4 overflow-auto">
        <h2 class="font-bold text-lg">Experiences and Skills</h2>
        <p class="text-sm md:text-base">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores earum
          ex provident pariatur mollitia corporis, laborum ratione recusandae,
          iste deserunt ab officiis consequuntur. Nostrum autem facere cum
          voluptatum consequuntur dolorem.
        </p>
        <div class="max-w-fit m-3 float-right">
          <router-link
            to="/skills"
            class="px-3 py-2 rounded-lg bg-green-300 text-gray-500"
            >Read more</router-link
          >
        </div>
      </article>

      <article class="border-2 rounded border-black m-10 p-4 overflow-auto">
        <h2 class="font-bold text-lg">Projects</h2>
        <p class="text-sm md:text-base">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores earum
          ex provident pariatur mollitia corporis, laborum ratione recusandae,
          iste deserunt ab officiis consequuntur. Nostrum autem facere cum
          voluptatum consequuntur dolorem.
        </p>
        <div class="max-w-fit m-3 float-right">
          <router-link
            to="/projects"
            class="px-3 py-2 rounded-lg bg-green-300 text-gray-500"
            >Read more</router-link
          >
        </div>
      </article>

      <article class="border-2 rounded border-black m-10 p-4 overflow-auto">
        <h2 class="font-bold text-lg">Contact</h2>
        <p class="text-sm md:text-base">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores earum
          ex provident pariatur mollitia corporis, laborum ratione recusandae,
          iste deserunt ab officiis consequuntur. Nostrum autem facere cum
          voluptatum consequuntur dolorem.
        </p>
        <div class="max-w-fit m-3 float-right">
          <router-link
            to="/contact"
            class="px-3 py-2 rounded-lg bg-green-300 text-gray-500"
            >Read more</router-link
          >
        </div>
      </article>
    </section>
  </div>
</template>
