<script>
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<section>
  <h3 class="md:text-2xl pb-3 font-extrabold tracking-widest">
    Current Dev Stack
  </h3>
  <ul class="text-base" transition:fly={{ x: 800, duration: 2000 }}>
    <li class="pb-3">Javascript(ES6)</li>
    <li class="pb-3">ReactJS</li>
    <li class="pb-3">Apollo</li>
    <li class="pb-3">GraphQL</li>
    <li class="pb-3">NodeJS</li>
    <li class="pb-12">Postgres</li>

  </ul>

</section>
