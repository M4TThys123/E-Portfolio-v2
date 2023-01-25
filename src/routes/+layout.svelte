<script>

import Nav from "../components/+nav.svelte";
  import About from "../components/+about.svelte";
  import TechStack from "../components/+tech-stack.svelte";
  import Projects from "../components/+projects.svelte";
  import Footer from "../components/+footer.svelte";
</script>


<div>
    <Nav></Nav>
    <main>  <!-- about me -->
        <About />
      
        <!-- tech stack -->
        <!-- <TechStack /> -->
      
        <!-- projects -->
        <Projects />
      </main>
      <slot/>

</div>
