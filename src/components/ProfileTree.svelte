<script>
  import About from "../components/sections/About.svelte";
  import DevStack from "../components/sections/DevStack.svelte";
  import Projects from "../components/sections/Projects.svelte";
  import AlmaMatter from "../components/sections/AlmaMatter.svelte";
  import Technology from "../components/sections/Technology.svelte";
  import Achievments from "../components/sections/Achievments.svelte";
  import Interests from "../components/sections/Interests.svelte";
  import { fly } from "svelte/transition";
</script>

<style>
  @media only screen and (max-width: 600px) {
    .alma {
      padding-left: 1.5rem;
      padding-right: 0px;
      margin-left: 1rem;
      margin-right: 0.5rem;
    }
  }
</style>

<div
  class="pl-10 pr-10 mr-10 ml-10 text-white alma"
  style=" border-left: 5px solid #a0aec0; position: relative ">
  <About />
  <AlmaMatter />
  <Projects />
  <DevStack />
  <Technology />
  <Achievments />
  <Interests />
</div>
