<script>
import Comics from './Comics.vue';
import SiteBanner from './SiteBanner.vue';

export default {
  name: "SiteMain",
  components: { SiteBanner, Comics }
}
</script>

<template>
  <main>
    <div class="main_content py-5">
      <div class="container ">
        <Comics />

      </div>

    </div>
    <SiteBanner />
  </main>

</template>

<style>

</style>
