<script>
import dc_comics from '../data/dc_comics.js'
export default {
    name: 'Comics',
    data() {
        return {
            fumetti: dc_comics
        }
    }
}
</script>

<template>

    <section class="fumetti_grid">
        <div class="container">
            <h3 class="badge">Current Series</h3>

            <div class="row">
                <div class="col">
                    <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                        alt="">
                    <p>Titolo</p>
                </div>
            </div>

        </div>

    </section>


</template>

<style>

</style>
