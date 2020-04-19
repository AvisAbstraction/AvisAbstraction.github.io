<script>
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<section>
  <h3 class="md:text-2xl pb-3 font-extrabold tracking-widest">
    Certification / Achievments
  </h3>
  <ul class="text-base" transition:fly={{ x: 800, duration: 2000 }}>
    <li class="pb-3">The Complete React-Native & Redux Course</li>
    <li />
    <li class="pb-12">
      <a
        href="https://www.codewars.com/users/Avinash-S95/badges/large"
        target="_blank"
        style="border-bottom:2px dotted white">
        6kyu rank holder in codewars
      </a>
    </li>
  </ul>

</section>
