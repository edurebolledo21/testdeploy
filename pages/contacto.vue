<template>
  <div>
    <form class="flex flex-col" action="">
      <div class="flex flex-row">
        <input type="text" name="nombre" />
        <label for="nombre">name</label>
      </div>
      <div class="flex flex-row">
        <textarea name="write" id="write" cols="30" rows="10"></textarea>
        <label for="write">what's problem?</label>
      </div>
      <button class="bg-slate-500 w-16" type="submit">send</button>
    </form>
    <br />
    <NuxtLink class="text-red-700" to="/">HOME</NuxtLink>
  </div>
</template>
