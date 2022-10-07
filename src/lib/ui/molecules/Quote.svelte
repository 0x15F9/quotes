<script>
  export let quote;
  export let author;
</script>

<section class="px-20">
  <h1 class="font-serif text-5xl text-green mb-8">{quote}</h1>

  <div class="flex items-center gap-4">
    <div class="border-b w-24" />
    <span class="text-xl">{author}</span>
  </div>
</section>
