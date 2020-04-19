<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from "../views/Home.svelte";
  import Blogs from "../views/Blogs.svelte";
</script>

<style>

</style>

<Router url="">
  <Route path="/" component={Home} />
  <!-- <Route path="blogs/" component={Blogs} /> -->

</Router>
