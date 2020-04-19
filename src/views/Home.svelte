<script>
  import Header from "../components/Header.svelte";
  import UserProfile from "../components/UserProfile.svelte";
  import ProfileTree from "../components/ProfileTree.svelte";
</script>

<style>

</style>

<div>
  <Header />
  <div class="container mx-auto md:px-2 sm:px-0 ">
    <div class="md:flex md:flex-row md:justify-center md:p-4 md:m-4 sm:block">
      <UserProfile />
      <ProfileTree />
      <!-- <div class="pt-10">right side</div> -->
    </div>
  </div>
</div>
