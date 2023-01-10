<script>
export default {
    data() {
        return {
            image: 'https://images.unsplash.com/photo-1444703686981-a3abbc4d4fe3?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80',
            alt: 'Immagine Jumbotron',
        }
    }
}
</script>

<template>
    <div>
        <img :src="image" :alt="alt">
    </div>
</template>

<style scoped>

</style>