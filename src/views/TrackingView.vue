<script setup lang="ts">
import InputTracking from "../components/input/InputTracking.vue"
</script>


<template>>
    <div class="container d-flex justify-content-center flex-column">
        <div class="container">
            <div class="container tracking-title">
                <h1 class="title text-center">
                    Lacak Pesanan
                </h1>
            </div>
        </div>
        <div class="container tracking-body d-flex flex-row align-items-center justify-content-between">
            <InputTracking />
            <div class="container tracking-img">
                <img src="https://troubleshoot.id/assets/illustration/trackingilu.svg" alt="Tracking">
            </div>
        </div>
        </div>
</template>

<style scoped>

.tracking-title .title {
    font-family: 'Quicksand', sans-serif;
}

.tracking-img {
    max-width: 100%;
    height: auto;
}

</style>