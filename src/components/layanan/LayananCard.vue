<template>
    <div class="container d-flex flex-row flex-wrap" id="layanan-cards">
        <div class="container d-flex flex-column justify-content-center" style="width: 20rem;" id="layanan-card" v-for=" item in $data">
            <div class="container card-image d-flex justify-content-center">
                <img :src="item.img" :alt="item.altImg">
            </div>
            <p class="card-tile text-center">{{ item.title }}</p>
        </div>
    </div>
</template>

<style scoped>
#layanan-cards {
    row-gap: 42px;
    padding: 30px 30px;
}
#layanan-card {
    row-gap: 42px;
}

img {
    max-width: 100px;
}

p {
    font-size: 18px;
    font-family: 'Poppins', sans-serif;
}
</style>

<script lang="ts">

const dataLayanan = [
    {
        title: "Perbaikan Laptop Mati Total",
        img: "https://troubleshoot.id/assets/images/service/motherboard.png",
        altImg: "MotherBoard"
    },
    {
        title: "Perbaikan Keyboard",
        img: "https://troubleshoot.id/assets/images/service/keyboard.png",
        altImg: "Keyboard"
    },
    {
        title: "Perbaikan LCD",
        img: "https://troubleshoot.id/assets/images/service/lcdrusak.png",
        altImg: "LCD"
    },
    {
        title: "Upgrade SSD",
        img: "https://troubleshoot.id/assets/images/service/ssd.png",
        altImg: "Upgrade SSD"
    },
    {
        title: "Upgrade RAM",
        img: "https://troubleshoot.id/assets/images/service/ram-memory.png",
        altImg: "Upgrade RAM"
    },
    {
        title: "Install Ulang",
        img: "https://troubleshoot.id/assets/images/service/installulang.png",
        altImg: "Install Ulang"
    },
    
]

export default {
    data () {
        return dataLayanan
    }
}


</script>