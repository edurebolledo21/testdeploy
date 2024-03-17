<template>
  <div>
    <NuxtLink to="/">
      <h1
        class="text-xl p-4 text-fuchsia-500 hover:text-slate-900 transition-all duration-300"
      >
        Hello Word
      </h1>
    </NuxtLink>
    <form class="px-4 flex flex-col gap-4 h-full" action="">
      <div class="flex flex-row gap-4">
        <input
          class="border-2 rounded outline-none border-black"
          type="text"
          name="nombre"
        />
        <label for="nombre">name</label>
      </div>
      <div class="flex flex-row gap-4">
        <textarea
          class="border-2 rounded outline-none border-black"
          name="write"
          id="write"
          cols="30"
          rows="10"
        ></textarea>
        <label for="write">what'ss problem?</label>
      </div>
      <button
        class="hover:bg-slate-500 transition-all duration-500 rounded-md w-16"
        type="submit"
      >
        send
      </button>
    </form>
    <br />
    <NuxtLink class="text-red-700" to="/">HOME</NuxtLink>
  </div>
</template>
