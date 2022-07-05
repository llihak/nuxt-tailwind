<template>
  <section>
    <div class="container mx-auto">
      <h1 class="text-3xl text-purple-700 font-extrabold">PowerTools page</h1>
      <div class="Powertools
                | grid grid-cols-1 md:grid-cols-2">
        <div class="powertool sm:flex md:flex-col">
          <div class="media">media</div>
          <div class="blurb">blurb</div>
        </div>
        <div class="powertool sm:flex md:flex-col">
          <div class="media">media</div>
          <div class="blurb">blurb</div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'PowerToolsPage'
}
</script>
