<script>
  import SocialMedia from "./SocialMedia.svelte";
  import { fly } from "svelte/transition";
</script>

<style>

</style>

<div transition:fly={{ x: -400, duration: 2000 }} class="mt-10">
  <div class="flex flex-col justify-center">
    <div class="mb-8 mx-auto">
      <img
        src="assets/my_pic.jpeg"
        alt="image"
        style="width: 150px; height: 150px; object-fit: cover; object-position:
        -70 0; margin-top: 0px; border-radius: 100%" />
    </div>
    <div class="text-white">
      <div class="mb-1 text-center">
        <p class="font-extrabold text-xl" style="letter-spacing:4px">
          Hi, I'm Avinash
        </p>
      </div>
      <div class="mb-1 text-center">
        <span class="text-gray-500">Trying to make Web an Awesome place</span>
      </div>
    </div>
  </div>
  <SocialMedia />
</div>
