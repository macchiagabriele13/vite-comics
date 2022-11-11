<script>
import Comics from './Comics.vue';
import SiteBanner from './SiteBanner.vue';
import Jumbo from './Jumbo.vue';

export default {
  name: "SiteMain",
  components: { SiteBanner, Comics, Jumbo }
}
</script>

<template>
  <main>
    <div class="main_content">
      <Jumbo />
      <div class="align-items-center container d-flex flex-column">

        <Comics />
        <div class="pb-4">
          <button class="bg-primary btn-primary p-2 px-5 text-light">Load More</button>

        </div>

      </div>

    </div>
    <SiteBanner />
  </main>

</template>

<style>

</style>
