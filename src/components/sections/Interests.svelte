<script>
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<section>
  <h3 class="md:text-2xl pb-3 font-extrabold tracking-widest">Interests</h3>
  <ul transition:fly={{ x: 800, duration: 2000 }}>
    <li class="pb-3">Keeping up with Tech Updates</li>
    <li class="pb-3">Fiddling with Linux OS</li>
    <li class="pb-3">Reading Articles & Books</li>
    <li class="pb-3">Exploring more on DevOPS & Data Science</li>
    <li class="pb-12">Watching YouTube Videos</li>

  </ul>

</section>
