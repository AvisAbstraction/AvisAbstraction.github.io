<script>
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<section>
  <h3 class="md:text-2xl pb-3 font-extrabold tracking-widest">Alma Matter</h3>

  <ul class="md:text-base" transition:fly={{ x: 800, duration: 2000 }}>
    <li class="pb-3">
      <div>
        Pursued my
        <strong>B.Tech</strong>
        in
        <span style="border-bottom:2px dotted white">
          <a
            target="_blank"
            href="https://www.veltech.edu.in/vel-tech-admissions/">
            Veltech University
          </a>
        </span>
        in 2013-2017
      </div>
    </li>
    <li class="pb-12">
      <div>
        Done my
        <strong>HSC</strong>
        and
        <strong>SSLC</strong>
        in
        <span style="border-bottom:2px dotted white">
          <a href="http://vmhss.org/" target="_blank">VMHSS</a>

        </span>
        Group of Schools
      </div>
    </li>
  </ul>

</section>
