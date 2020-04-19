<script>
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<section>
  <h3 class="md:text-2xl pb-3 font-extrabold tracking-widest ">Who ?</h3>
  <ul
    class="md:text-base xs:text-xs"
    transition:fly={{ x: 800, duration: 2000 }}>
    <li class="pb-3">Full Stack Developer (by Profession)</li>
    <li class="pb-3">Data Science (Enthusiast)</li>
    <li class="pb-12">Hailing in Chennai</li>
  </ul>

</section>
