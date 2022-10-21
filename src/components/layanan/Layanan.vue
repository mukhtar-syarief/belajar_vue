<script setup lang="ts">
import LayananCard from "./LayananCard.vue"
</script>

<template>
    <div class="container d-flex justify-content-center layanan-title">
        <h5>Layanan Troubleshoot.id</h5>
    </div>
    <div class="container layanan-wrap d-flex flex-row flex-wrap">
        <LayananCard />
    </div>
</template>

<style scoped>
.layanan-title h5 {
    padding: 10px;
    font-size: 42px;
    font-weight: 900;
    color: rgb(27, 27, 27);
}


</style>