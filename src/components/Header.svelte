<script>
  import { Link } from "svelte-routing";
  import { fade } from "svelte/transition";
</script>

<style>

</style>

<div
  transition:fade={{ duration: 2000 }}
  class="bg-purple-700 text-white font-extrabold text-center p-4"
  style="background-color:#2b304c">
  <div class="container">
    <span>About</span>
    <span>/</span>
    <span>Blogs</span>

  </div>
</div>
