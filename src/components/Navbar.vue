<template>
  <ul class="text-right p-4 font-semibold bg-gray-100 mr-4">
      <li class="inline mx-2 text-pink-600 hover:text-pink-400 cursor-pointer" v-for="link in links" v-bind:key="link">{{link}}</li>
  </ul>
</template>

<script>
export default {
 name: 'Navbar',
 props: {
    links: [String]
 },
//  data: () => ["home", "about", "contact"]
}
</script>

<style>

</style>