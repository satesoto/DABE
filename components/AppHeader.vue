<template>
    <div class="bg-header-landing-color">
    <div class="bg-header-landing">
        <h1>DABE</h1>
        <div class="navbar-landing">
            <p>Produk</p>
            <p>Testimoni</p>
            <p>Tentang</p>
            <p>Masuk</p>
            <p class="button-signup">Daftar</p>
        </div>
    </div>
    </div>
</template>

<style scoped>
.bg-header-landing-color {
        background: #22AB9721;
        width: 100wh;
        font-family: poppins;
}

.bg-header-landing {
    width: 80%;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 2rem;
}

.navbar-landing {
    display: flex;
    align-items: center;
    gap: 2rem;
    
}

h1 {
    color: #22AB97;
    font-weight: 700;
    font-size: 27px;
    letter-spacing: 1px;
}

p {
    color: #6F6969;
    font-weight: 600;
    font-size: 15px;
    letter-spacing: 1px;
}

p:hover {
    color: #22AB97;
    cursor: pointer;
}

.button-signup {
    padding: 5px 20px;
    border-radius: 7.15px;
    color: #ffffff;
    background-color: #22AB97;
}

.button-signup:hover {
    color: #ffffff;
    background-color: #1B8979;
    cursor: pointer;
    transition: 0.3s ease-in-out;
    transform: scale(1.02);
}
</style>
