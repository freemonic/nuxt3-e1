<script setup lang="ts"> 
    import { useRoute } from "vue-router"

    const route = useRoute()
    console.log(route)
    console.log(route.params)
    console.log(route.params.id)
</script>

<template>
    <div>event id: {{ $route.params.id }}</div>
</template>