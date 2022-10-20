<template>
    <div class="img-banner d-flex justify-content-end">
        <p>
            <img src="https://troubleshoot.id/assets/images/landing.png" alt="Welcome">
        </p>
    </div>
    <div class="d-flex flex-column justify-content-center detail-banner">
        <h3 class="banner-title">Laptop kamu lemot? Keyboard kamu rusak?</h3>
        <h4> TROUBLESHOOT.ID AJA </h4>
        <p>kini <span>TROUBLESHOT.ID</span> hadir sebagai solusi permasalahan untuk laptop kesayanganmu</p>
        <p>Konsultasikan permasalahan laptopmu di sini!</p>
        <p class="konsultasi"><a href="" type="button" class="konsultasi-btn">Konsultasi</a></p>
    </div>
</template>


<style scoped>
*{
  font-family: 'Quicksand', sans-serif;
}

div {
    padding: 0 16px;
}

.img-banner img {
    max-height: 20rem;
    width: auto;
}

.detail-banner {
    max-width: 540px;
    row-gap: 18px;
}

h3 {
    font-size: 1.75rem;
    font-weight: 600;
}

h4 {
    font-family: 'Ropa Sand', sans-serif;
    font-weight: 700;
}

p {
    font-weight: 700;
    font-size: 16px;
}

span {
    font-weight: 700;
    font-family: 'Ropa Sans', sans-serif;
}

.konsultasi-btn {
    font-size: 18px;
    color: white;
    padding: 6px 50px;
    background-color: #17a2b8;
    border-radius: 10px;
}
</style>