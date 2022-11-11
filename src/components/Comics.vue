<script>
import dc_comics from '../data/dc_comics.js'
import Comic from '../components/Comic.vue'
export default {
    name: 'Comics',
    components: {
        Comic,
    },
    data() {
        return {
            comics: dc_comics
        }
    }
}
</script>

<template>

    <section class="fumetti_grid">
        <div class="container">
            <h3 class="badge">Current Series</h3>

            <div class="row ">
                <Comic v-for="comic in comics" :image='comic.thumb' :category='comic.series' />
                <!-- <div class="col-2" v-for="comic in comics">
                    <img :src="comic.thumb" alt="">
                    <p>{{ comic.series }}</p>
                </div> -->
            </div>

        </div>

    </section>


</template>

<style>

</style>
