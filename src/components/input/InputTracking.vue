<template>
    <div class="container input-tracking d-flex align-items-end">
        <div class="container input d-flex flex-column input">
            <input type="text" class="container w-100" placeholder="Masukkan ID Pesanan contoh : XXXXXX65123YZH">
            <button type="submit">Lacak Pesanan</button>
        </div>
    </div>
</template>


<style scoped>
.input {
    row-gap: 20px;
}

.input input {
    border: none;
    border:2px solid #1290b6; 
    height: 42px;
    border-radius: 6px;
    text-indent: 10px;
    line-height: 1.5;
}

.input input::placeholder {
    font-family: 'Poppins', sans-serif;
    font-size: 16px;
    padding-left: 10px;
}

.input input:focus {
    outline: none;
    border:2px solid #1290b6;
}

.input button {
    background: none;
    border: none;
    color: white;
    font-size: large;
    font-family: 'Quicksand', sans-serif;
    font-weight: 600;
    background-color: #1290b6;
    border-radius: 8px;
    padding: 6px 0;
}
</style>