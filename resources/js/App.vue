<template>
    <div>
        App
        <router-link to="index">Index</router-link>
        <router-link to="page">Page</router-link>
        <router-view></router-view>
    </div>
</template>

<script>
export default {
    name: "App",
}
</script>


<style scoped>

</style>
