<script setup></script>
<template>
  <div class="mt-10 md:mt-28 p-2 text-center md:text-left max-w-5xl">
    <h1
      class="text-3xl md:text-5xl text-transparent bg-clip-text bg-gradient-to-r from-green-400 to-sky-400"
    >
      Welcome! My name is Jeroen. I'm a software developer.
    </h1>
    <h2 class="text-2xl md:text-4xl md:mt-5 mt-3 text-white">
      This place is made with
      <a
        class="text-green-400 hover:text-green-800 text-bold"
        href="https://nuxt.com/"
        >Nuxt</a
      >
    </h2>
    <h3 class="text-xl md:text-2xl md:mt-4 mt-2 text-white">
      For styling this one I use
      <a
        class="text-sky-500 hover:text-sky-800 text-bold"
        href="https://tailwindcss.com/"
        >Tailwind</a
      >
    </h3>
    <div class="md:border md:border-slate-200 mt-5 md:mt-8 md:p-5 p-2">
      <p class="text-md md:text-xl text-white tracking-wide">
        I'm currently working a lot with JavaScript. Building user interfaces
        with the help of the
        <a
          class="text-green-400 hover:text-green-800 text-bold"
          href="https://vuejs.org/"
          >Vue</a
        >
        ecosystem, using tools like
        <a
          class="text-green-400 hover:text-green-800 text-bold"
          href="https://nuxt.com/"
          >Nuxt</a
        >
        and
        <a
          class="text-sky-300 hover:text-sky-800 text-bold"
          href="https://vuetifyjs.com/en/"
          >Vuetify</a
        >. And I'm starting to dive a bit more into
        <a
          class="text-sky-600 hover:text-sky-800 text-bold"
          href="https://www.python.org/"
          >Python</a
        >
        programming. My interests lie in building rest api's with the help of
        <a
          class="text-red-600 hover:text-sky-300 text-bold"
          href="https://www.django-rest-framework.org/"
          >Django Rest Framework</a
        >
        and getting a grip of AI and ML where I use
        <a
          class="text-sky-600 hover:text-sky-300 text-bold"
          href="https://flask.palletsprojects.com/en/2.3.x/"
          >Flask</a
        >
        to make my discoveries visible on the web.
      </p>
    </div>
    <div class="flex mt-5 md:mt-8 gap-4">
      <div
        class="text-white text-sm md:text-lg basis-1/2 border border-grey-200 p-2 md:p-5 flex flex-col gap-y-3"
      >
        <p>
          Over here you'll find blog posts, just reminders to myself and stuff
          related to JavaScript, Vue and Nuxt.
        </p>
        <button
          @click="navigateTo('/javascript')"
          class="px-2 py-1 md:px-4 md:py-2 mt-5 border border-slate-200 bg-emerald-600 hover:bg-emerald-800 mt-auto"
        >
          Read more about JavaScript
        </button>
      </div>
      <div
        class="text-white text-sm md:text-lg basis-1/2 border border-grey-200 p-2 md:p-5 flex flex-col gap-y-3"
      >
        <p>
          And if you click on this one you'll read all about my Python journey
          with Flask and Django Rest Framework.
        </p>
        <button
          @click="navigateTo('/python')"
          class="px-2 py-1 md:px-4 md:py-2 border border-slate-200 bg-emerald-600 hover:bg-emerald-800 mt-auto"
        >
          Read more about Python
        </button>
      </div>
    </div>
  </div>
</template>
