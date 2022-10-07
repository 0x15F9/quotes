<script lang="ts">
  import Navbar from "./lib/ui/molecules/Navbar.svelte";
  import Quote from "./lib/ui/molecules/Quote.svelte";

  let quote =
    "When we strive to become better than we are, everything around us becomes better too";
  let author = "Paulo Coelho";
</script>

<main class="bg-beige h-screen">
  <Navbar />
  <div class="mt-24" />
  <Quote {quote} {author} />
</main>

<style>
</style>
