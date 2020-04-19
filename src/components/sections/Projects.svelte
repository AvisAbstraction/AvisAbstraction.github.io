<script>
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<section>
  <h3 class="md:text-2xl pb-3 font-extrabold tracking-widest">Projects</h3>
  <ul class="text-base" transition:fly={{ x: 800, duration: 2000 }}>
    <li>
      <strong class="tracking-widest">DPHPM</strong>
    </li>
    <li class="pb-5">
      <span class="block pb-2">
        <span style="border-bottom:2px dotted white">
          <strong>Sanitation</strong>
        </span>
        - Module for registering sanitation certificate with role based
        authentication system
      </span>
      <span class="block pb-2">
        <span style="border-bottom:2px dotted white">
          <strong>Cancer Registry</strong>
        </span>
        - Module for registering cancer patients
      </span>
      <span class="block">
        <span style="border-bottom:2px dotted white">
          <strong>CDSP</strong>
        </span>
        - Communicable Disease Surveillance Portal
      </span>

    </li>
    <li>
      <strong class="tracking-widest">
        <a
          href="https://www.pinecrow.com/"
          target="_blank"
          style="border-bottom:2px dotted white">
          Pinecrow
        </a>
      </strong>
    </li>
    <li class="pb-5">An Overall Project Management App</li>
    <li>
      <strong class="tracking-widest" I>
        <a
          href="https://www.stylori.com/"
          target="_blank"
          style="border-bottom:2px dotted white">
          NAC jewellers
        </a>
      </strong>
    </li>
    <li class="pb-12">An e-commerce website for buying jewellers</li>
    <li />
  </ul>

</section>
