<script>
export default {
    props: {
        image: String,
        category: String,
    }
}
</script>

<template>


    <div class="col-2">
        <img :src="image" alt="">
        <p>{{ category }}</p>
    </div>



</template>

<style>

</style>
